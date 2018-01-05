# 100 Days Of Code - Log

### Day 1: Dec 28 2017, Thursday

**Today's Progress**: I set up a create-react-app bootstrap for my app: a front-end for Deimos 2147 (a webgame I'm writing). I made a git repo for it and uploaded my first few commits playing around with react. I also learned how to use the react development server's hot-reload feature.

**Thoughts**: React is really neat and I'm excited to continue learning it. I like the simplicity combined with the power to do complex things.

**Link(s) to work**
1. [Latest commit](https://github.com/tigwyk/deimos-react/commit/0880de83c7b15d1f3ea3ba75b7097ae74279a02f)

### Day 2: Dec 29 2017, Friday

**Today's Progress**: I attempted to write a rudimentary fetch lookup of the API I exposed from Deimos 2147 and mostly failed, but I learned a lot in the process. I scaled down my attempts and I may have it working soon.

**Thoughts**: Combining React and python Flask is ... difficult, to say the least.

**Link(s) to work**
1. [Latest commit to deimos-react](https://github.com/tigwyk/deimos-react/commit/c03c603c31d6e8097b51f48a8386bdf816ef239b)
2. [Latest commits to Deimos 2147](https://github.com/tigwyk/spacerpg/commits?author=tigwyk&since=2017-12-29T08:00:00Z&until=2017-12-30T08:00:00Z)

### Day 3: Dec 30 2017, Saturday

**Today's Progress**: I finally got the basic fetch API call working with cookies so that it properly has access to the character API endpoint and can show character name, attributes, etc. Took me the entire hour to get this working after trying various methods.

**Thoughts**: I'm ecstatic that I've combined Flask-Login to handle authentication along with the API and the ReactJS front-end to manage the visual aspect of where all the API results end up on the page. This is FASCINATING!

**Link(s) to work**
1. [Latest commits to deimos-react](https://github.com/tigwyk/deimos-react/commits/master)
2. [Latest commits to Deimos 2147](https://github.com/tigwyk/spacerpg/commits/master)

### Day 4: Jan 1 2018, Monday

**Today's Progress**: I poked around at the React Material Components for Web library and added a LayoutGrid to see how the data looks. It's... not laid out properly but we're getting somewhere!

**Thoughts**: This library was difficult to use since I wasn't aware of all the pieces I needed to install beforehand.

**Link(s) to work**
1. [Latest commits to deimos-react](https://github.com/tigwyk/deimos-react/commits/master)
2. [Latest commits to Deimos 2147](https://github.com/tigwyk/spacerpg/commits/master)

### Day 5: Jan 2 2018, Tuesday

**Today's Progress**: Tried to fix a bug with ReactJS not authenticating properly with Flask from other computers. Two separate computers, two failed attempts at authenticating. I can login, but the API calls don't seem to use the proper credentials so they return a weird error.

**Thoughts**: I don't even know what's going on with this bug. I keep adding checks and it keeps bypassing them. Tomorrow's another day.

**Link(s) to work**
1. [Latest commits to Deimos 2147](https://github.com/tigwyk/spacerpg/commits/master)

### Day 6: Jan 3 2018, Wednesday

**Today's Progress**: I think I fixed the pesky ReactJS/Flask API authentication bug and now I'm trying to clean up the CSS so that it looks prettier. 

**Thoughts**: Not sure what I did to fix the bug really aside from making the API call local instead of specifying the whole URL, maybe that was all it took. CSS is proving to be a little frustrating though.

**Link(s) to work**
1. [Latest commits to Deimos 2147](https://github.com/tigwyk/spacerpg/commits/master)
2. [Latest commits to deimos-react](https://github.com/tigwyk/deimos-react/commits/master)

### Day 7: Jan 4 2018, Thursday

**Today's Progress**: I copied the material components CSS and JS files to their respective directories in the static/ directory of the Flask project in order to apply the right CSS stylings to the layout grid I'm using. I also threw in a new cell for showing the players credits. 

**Thoughts**: CSS still frustrates the heck out of me, heh.

**Link(s) to work**
1. [Latest commits to Deimos 2147](https://github.com/tigwyk/spacerpg/commits/master)
2. [Latest commits to deimos-react](https://github.com/tigwyk/deimos-react/commits/master)
