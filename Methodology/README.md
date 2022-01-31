# Methodology
Porky's Methodology. Please read Licensing HERE: https://github.com/linkinporkHF/grimoire/blob/main/LICENSE


## What is the Penetration Testing Life Cycle
![Penetration Testing Cycle](https://www.securnite.com/wp-content/uploads/2018/10/Penetration-Testing-Lifecycle.png)
Source: https://www.securnite.com/wp-content/uploads/2018/10/Penetration-Testing-Lifecycle.png

`IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.`


## Parts of the Pentest Life Cycle
- **Reconnaissance/Information Gathering**: learn about your target from the outside - use search engines, Wayback Machine, pastebin, leaked databases
- **Enumeration/Attack surface mapping**: learn about your target by touching it - use directory fuzzers, port mappers, website crawlers
- **Vulnerability Analysis**: use scanners, check the architecture for unpatched items, basic heuristic tests
- **Exploitation**: use the vulns you got from Vulnerability Analysis and test the bugs, see if they work
- **Post-exploitation**: chain the bugs after proving they work, attempt to see if you can create bigger, more severe effects, hopefully after shell has been achieved
- **Reporting**: Pull together what you've found out

## Notes, Some tips

- Sharpen up on your Google Dorks for the Information Gathering stage and try to memorize the basic keywords
- If you need wordlists and dictionaries for your fuzzers during Enumeration, try this one https://github.com/danielmiessler/SecLists
- Use the NVD as reference for cross-checking CVE applicability during Vuln Analysis stage https://nvd.nist.gov/vuln/search
- Don't be afraid to use Metasploit during Exploitation stage, we can't expect you to make your own scripts every single time
- Post-Exploitation is very dependent on the bugs you've proven in Exploitation, so don't worry if you can't do much here
- Finally, make sure you reward yourself after all is done - get like a pint or whatever

## Notes, Relevant links

- Google Hacking Database https://www.exploit-db.com/google-hacking-database
- National Vulnerability Database https://nvd.nist.gov/vuln/search
- Exploit Database https://www.exploit-db.com/