# Node.js EventLoop Visualizer Client

## **UPDATE** This repo has been moved [here](https://github.com/vagostep/Node-EventLoop-Visualizer)

![Demo of the Node-Event-Loop](event-loop-visualizer.gif)

Try it out! [Node-Event-Loop](https://node-event-loop.herokuapp.com/)

This Event Loop Visualizer shows the phases that an Event Loop makes when executing Javascript code. The server captures the traces at runtime and then, it returns them to the visualizer.

### What's new?

* Added feature to support actual Node.js Event Loop & processTicksAndRejections traces
* Added better visualization of Node.js' Event Loop phases
* Added a visualizer of the processTicksAndRejections loop
* Added a "terminal" to print logs with an Ubuntu skin
* New examples and descriptions


# Dependencies 

* The repo for the backend service is [here](https://github.com/andresdiaz29/Node-EventLoop-Visualizer-Server).
* The repo for the Node.js modified source code is [here]()

# How to run it?

```
npm install
npm run start
```

# Supported Features

* Promise.resolve().then()
* Promise.reject().catch()
* new Promise((resolve) => resolve()).then 
* process.nextTick()
* queueMicrotask()
* setTimeout()
* setInterval() (You need to add a clearInterval() at some point to spot the execution)
* fs.readFile()
* setImmediate()

# Issues

If you find any issue, please open a new issue

# Feature Requests

If you want to test some functionality that is not supported yet, please open a ticket request.

# Acknowledgments

This repo is an improvement of the wonderful work made by 
<table>
  <tr>
    <td align="center">
      <a href="https://github.com/PhakornKiong">
        <img src="https://github.com/PhakornKiong.png" alt="PhakornKiong" width="100" />
      </a>
      <br />
      <a href="https://github.com/PhakornKiong">PhakornKiong</a>
    </td>
    <td align="center">
      <a href="https://github.com/Hopding">
        <img src="https://github.com/Hopding.png" alt="Hopding" width="100" />
      </a>
      <br />
      <a href="https://github.com/Hopding">Hopding</a>
    </td>
    <td align="center">
      <a href="https://github.com/latentflip">
        <img src="https://github.com/latentflip.png" alt="latentflip" width="100" />
      </a>
      <br />
      <a href="https://github.com/latentflip">latentflip</a>
    </td>
    <td align="center">
      <a href="https://github.com/thedull">
        <img src="https://github.com/thedull.png" alt="thedull" width="100" />
      </a>
      <br />
      <a href="https://github.com/thedull">thedull</a>
    </td>
  </tr>
</table>
