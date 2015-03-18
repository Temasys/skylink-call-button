# &lt;skylink-call&gt;

Web-Component to embed a button into your website to call another visitor via WebRTC powered by [SkylinkJS](http://skylink.io/web).


## Usage

```html
<skylink-call app-key="Your APP key" caller-id="Your ID" caller-name="Your Name" callee-id="Callee ID" callee-name="Callee Name"></skylink-call>
```

What to know?
- Ideally use your apps user id as `caller-id`/`callee-id`
- Set the `callee-id` and `callee-name` attributes depending on who you want to call
- From on the second button on your website you don't need to set `app-key`, `caller-id` and `caller-name` attributes anymore.
- There is no guarantee you will always reach the person you want to talk to as everybody could potentially impersonate any `caller-id`
- Get an APP key [here](http://developer.temasys.com.sg)


## Demo

Try it and open the following three links in seperate tabs or on different devices

- [Be Alice](https://temasys.github.io/skylink-call-button/alice.html)
- [Be Bob](https://temasys.github.io/skylink-call-button/bob.html)
- [Be Charles](https://temasys.github.io/skylink-call-button/charles.html)


## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

* Install [Bower](http://bower.io/) & [Grunt](http://gruntjs.com/):

```sh
$ [sudo] npm install -g bower grunt-cli
```

* Install local dependencies:

```sh
$ bower install
```


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D


## License

Apache 2.0
