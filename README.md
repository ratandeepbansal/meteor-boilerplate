# Meteor Boilerplate

For starting new projects. I tried to include files that utilize the provided packages as a reference on how to use them. They are in Coffeescript at the moment. If you like Javascript you can still get the gist of how I'm using them - just ignore/delete them as they are not required.

## Packages

```
meteor-platform
coffeescript
iron:router
aldeed:collection2
matb33:collection-hooks
accounts-password
momentjs:moment
reywood:publish-composite
dburles:collection-helpers
reactive-var
zimme:active-route
alanning:roles
dburles:factory
digilord:faker
msavin:mongol
```

## Usage

### Clone and rename

```
git clone git@github.com:webtempest/meteor-boilerplate.git projectname
cd projectname
```

### Pick javascript langauge (optional)

#### Coffeescript (`.coffee`)

This is actually in there already so you don't need to add this. But in case you want to know.

```
meteor add coffeescript
```

#### ES6 (`es6.js`, `.es6` or `.jsx`)

```
meteor add grigio:babel
```


### Pick stylesheet language (optional)

#### Sass

```
meteor add fourseven:scss
```

#### Less

```
meteor add less
```


### Pick style

#### Bootstrap

```
meteor add twbs:bootstrap
meteor add useraccounts:bootstrap
```

#### Semantic UI

```
meteor add semantic:ui flemay:less-autoprefixer
meteor add useraccounts:semantic-ui
```

#### Materialize

```
meteor add materialize:materialize
meteor add useraccounts:semantic-ui
```

### If you want a loader

This is a local package. It basically is a copy of [meteor-auto-nprogress](https://github.com/settinghead/meteor-auto-nprogress/blob/master/auto-nprogress.js), but differs in that I modified nprogress a bit to make is compatible with Meteoric ([my PR for nprogress](https://github.com/rstacruz/nprogress/pull/128/files)).

Basically shows a progress bar on the top of the screen like YouTube while subscriptions load. Loader used: http://ricostacruz.com/nprogress

```
meteor add mplatts:meteor-loader
```

### Remove helper files

There are files dotted around in certain folders to help you get started. Mostly you can just keep them there and use them as a reference. Though you'll probably want to change `/both/routes`.

## Decisions

### Iron Router vs Flow Router

I use Iron Router because I like Meteoric, which needs Iron Router. You can switch for Flow Router if you aren't using Meteoric though.

### Folder/files

Folder/file naming and patterns used are opinionated and open for debate. Please create issues or PR's for suggested new patterns.

### Coffeescript vs Javascript

I've used both professionally and Coffeescript is a hands down winner - makes coding quicker and more enjoyable with no real downsides. I wrote [a blog post](http://www.webtempest.com/learn-coffeescript-fast) to help people learn it quickly (only takes about 15-30 mins to learn). Well worth it I promise.
