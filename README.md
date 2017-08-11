# New Shell for 'SMU Enrolling System'

## Compile
Firstly, install two packages globally: `pug-cli` and `stylus`.

```(shell)
npm install --global pug-cli stylus
```

then,

```(shell)
./compile
```

and everything you need is lying comfortably in `bin`.


## Branch & GitHub Pages
Branch `master` includes source code (which are coded in Pug and Stylus) and
compile script.

Branch `gh-pages` is *exactly* what directory `bin` is. If there is any change
in branch `master`, it should be compiled and deployed into `gh-pages` eventually.


## Security
It cannot handle the native page because of some security issues.

It is:
- not a reverse-proxy;
- using `iframe` to cross domain, but not (cannot) manipulate or read it.


## License
It is under the version 3 of the GNU General Public License.

http://www.gnu.org/licenses/gpl-3.0.html
