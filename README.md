# New Shell for 'SMU Enrolling System'

I never optimistically think there will be any change on the
aesthetic enrolling page. This 'redesigned' that terrible shit in some way.

## Branch & GitHub Pages
Branch `master` includes source code (which are coded in Pug and Stylus) and
compile script.

Branch `gh-pages` is *exactly* what directory `bin` is. If there is any change
in branch `master`, it should be compiled and deployed into `gh-pages` eventually.


## Security
It cannot handle the native page because of some security issues.

It is:
- not a reverse-proxy;
- using `iframe` to cross domain, but not manipulate or read it.

## License
It is under the version 3 of the GNU General Public License.

http://www.gnu.org/licenses/gpl-3.0.html

## When will this be out-of-date?
This project is based on:
- an **aesthetic** design;
- a stack of useless functions while it should be no more than a transition between the offer and the CAS;
- totally out-of-date code.
