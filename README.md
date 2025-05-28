# Peer-to-peer mini r/place with Proof of Work
*or "SHA256 Battle"*

----
Project + code: https://tropical.pages.dev/pow/

I haven't uploaded the code here but you can see it by viewing the source of the webpage linked above. It's JavaScript.

----
## Screenshots:
|<img width="540" alt="image" src="https://github.com/user-attachments/assets/ab81ab5f-e26f-494e-94ad-ddf4ba3d59ea" />|<img width="506" alt="image" src="https://github.com/user-attachments/assets/e3c5e396-b0c7-4114-9d8f-be1a97b137c0" />|
|---|---|
<img width="575" alt="image" src="https://github.com/user-attachments/assets/a53da834-aa2f-407b-8063-19ab83bf50ca" />

## What is it?
- Who has mined the hardest will have their text shown on the website.
- There is also a small wall of pixels. Each pixel can be mined. And it's possible to "vote" on the best color.
- Proof of Work with basic gossip over P2P (STUN/TURN)
- e.g. for text: the smallest sha256(nonce + text) value seen in P2P network should be displayed on top of this page *[1]*

*[1] nonce placement could be improved*

## Current State
- People found some nice hashes. Best hash of text: ``00000000000003f5b562d3feca28eadb16ef1e2f051550344f62f1848e3d3dc6``
- It was a fun experiment. There were more ideas for it, but the project hasn't been worked on for a while.
- Maintaining STUN/TURN etc. was annoying so I don't do it anymore. The best submissions (best hashes) have been cached.



----
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
