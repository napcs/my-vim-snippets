my-vim-snippets
===============

My cusomized shortcuts for vim's SnipMate plugin

## HTML
* `html5t` generates an HTML5 skeleton
* `html5js` generates an HTML5 skeleton with inline JS
* `ijs` generates `script` blocks for inline JS
* `image` generates image tag with alt
* `csslink` generates a `link` tag for CSS
* `jqueryref` generates a call to load jQuery from CDN
* `jslink` generates link to call external JS
* `textfield` generates `label` and `input type="text"`
* `textfieldbr` generates `label` and `input type="text"` with a `<br>` between
* `textarea` generates `label` and `textarea`
* `textareabr` generates `label` and `textarea` with a `<br>` between
* `emailfield` generates `label` and `input type="email"`
* `emailfieldbr` generates `label` and `input type="email"` with a `<br>` between
* `select` generates `label` and `select` and a default `<option>`
* `selectbr` generates `label` and `select` with a `<br>` between, with a default `<option>` between
* `number` generates `label` and `input type="number"`
* `numberbr` generates `label` and `input type="number"` with a `<br>` between
* `checkbox` generates `label` and `input type="checkbox"`
* `checkboxbr` generates `label` and `input type="checkbox"` with a `<br>` between
* `radio` generates `label` and `input type="radio"`
* `radiobr` generates `label` and `input type="radio"` with a `<br>` between
* `brow` generates a `div` with class `row`
* `bcol` generates a `div` with class `col-sm-` and a placeholder
* `bcolmd` generates a `div` with class `col-md-` and a placeholder
* `btn-primary` generates a `button` with class `btn btn-primary`
* `btn-secondary` generates a `button` with class `btn btn-secondary`
* `abtn-primary` generates an `a` with class `btn btn-primary`
* `abtn-secondary` generates an `a` with class `btn btn-secondary`
* `viewport` generates a default meta viewport for mobile


## CSS

* `100%` - html, body, .container, main {height: 100%;}
* `mediamin` is a min-width media query


## JavaScript
* `object` generates skeleton for object literal
* `objectkey` generates the skeleton for an object as a key
* `anon` generates anonymous function
* `listen` generates `.addEventListener`
* `keyval` generates a sinple key: value snippet
* `dce` is `document.createElement`
* `dgt` is `document.getElementsByTagName`
* `dgi` is `document.getElementById`
* `ac` is `appendChild`
* `prompt` is a prompt box
* `number` is the `Number` function
* `tof` is `toFixed`
* `dw` is `document.write`
* `dw"` is `document.write("")`
* `ael` is `addEventListener`
* `iah` - `insertAdjacentHTML`
* `forof` is a `for x of y` loop
* `map` is a map function
* `reduce` is a reduce function
* `reduce>` is a reduce arrow function
* `ifenter` - if event for character 13 found....
* `todo` puts in a TODO with datestamp
* `note` puts in a NOTE with datestamp
* `fixme` puts in a FIXME with datestamp

### Grunt

* `gruntfile`  creates skeleton for Gruntfiles
* `gtask`  creates skeleton for a task
* `gnpm`  generates `grunt.loadNPMTasks`
* `ginitconfig` generates the initConfig code skeleton
* `gconfig` generates the `grunt.config` modular style of config
* `gll` generates `grunt.log.writeln`
* `gw` generates `grunt.warn`
* `gcg` generates `grunt.config.get`

### Phoenix JS
* `schan` - create a channel
* `cjoin` - Join a channel with ok and error callbacks
* `con` - Receive channel event
* `cpush` - Push message to channel with receive callbacks


## Ruby

* `todo` puts in a TODO with datestamp
* `note` puts in a NOTE with datestamp
* `fixme` puts in a FIXME with datestamp

## Elixir and Phoenix
* `todo` puts in a TODO with datestamp
* `note` puts in a NOTE with datestamp
* `fixme` puts in a FIXME with datestamp
* `redirect` - Phoenix redirect
* `render` - Phoenix render
* `ef` - Enum.filter (piped)
* `efl` - Enum.filter (takes list)
* `em` - Enum,map (piped)
* `eml` - Enum.map (takes list)
* `er` - Enum.reduce (piped)
* `erf` - Enum.reduce (takes list)
* `ej` - Enum.join
* `ttl` - Tuple.to_list
* `sha` - `:crypto.hash(:sha, value)`
* `encode16` - Base.encode16
* `slice` - String.slice(${0})
* `join` - Join function for channel
* `inspect` - IO.inspect
* `broadcast_from` - Phoenix Channel broadcast_from
* `handle_in` - Phoenix Channel handle_in with reply
* `if_ok` - Phoenix macro for conditional piping
* `escript` - Configure escript
* `genserver` - Basic Genserver template
* `config_extwitter` - Configuration for ExTwitter library
* `handle_cast` - GenServer handle_cast
* `pchannel` - Phoenix Channel template
* `dep_oauth` - Oauth dependency
* `dep_extwitter` - ExTwitter dependency
* `spawn` - Spawn
* `spawn_link` - Spawn_link
* `ExTwitter.sf` ExTwitter stream_filter
