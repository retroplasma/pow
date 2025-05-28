# Peer-to-peer mini r/place with Proof of Work
*or "SHA256 Battle"*

----

Project + code: https://tropical.pages.dev/pow/

You can see the code by viewing the source. It's JavaScript.

## What is it
- Who has mined the hardest will have their text shown on the website.
- There is also a small wall of pixels. Each pixel can be mined.
- Proof of Work
- Text of the smallest sha256(nonce + text) value seen in P2P network should be displayed on top of this page *[1]*

## Current State
Maintaining STUN/TURN etc. is annoying so I didn't do it. The best submissions (best hashes) have been cached.

----

*[1] not the most ideal nonce placement*



----
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
