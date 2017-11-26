# butlerbot-redbrick-committee

redbrick committee plugin for butlerbot


## Install

```sh
yarn add butlerbot-redbrick-committee
```
Create a file in the plugin dir as follows

```js
import cmt from 'butlerbot-redbrick-committee';
export default cmt({
  development: {
    "url": "http://redbrick.dcu.ie/api/committee",
    channels: ['#butlerbot'],
    channelsToExclude: [],
    channelsToJoin: ['#butlerbot'],
  },

  production: {
    "url": "http://redbrick.dcu.ie/api/committee",
    channels: ['#butlerbot'],
    channelsToExclude: [],
    channelsToJoin: ['#butlerbot'],
  },
  "postions": [
    "System Administrator",
    "Chairperson",
    "Secretary",
    "Public Relations Officer",
    "Treasurer",
    "Events Officer",
    "Helpdesk",
    "First Year Representative"
  ]
});
```
