# Badger Protocol Specifications:
# Who controls it:
The official registry is controlled by the BDSA (Badger Domain Server Authority)
You register a site via Namebeans (The registrar)
# The client side:
A person wishing to access a badger "Port" also known as a Domain "eg; example.org". These "Ports" are typed in as "domain-name.tld" and the client checks a master record YAML file that maps a Port to well, a literal "BPORT" typed out as: 0001 (The equivalent of a IP.) Must use a Badger Client: eg; Badgium
# Developer Side:
# Client:
Making a Badger client is pretty easy. All you need is:
- a way of using the Master YAML File API (By BDSA) (Badger Domain Server Authority)
- a way of displaying Badger Markup (BML) and Text.
- Connecting to a domain (Obviously)
- Use GNU GPL v3
# Server:
Well, In order to make a Server you need to:
Register a BPORT and provide a BML file.
Register a Domain from Namebeans and assign it a BPORT
# Webpage:
Badger uses the Badger Markup Language (BML)
This means that when making a webpage, you need to use badger markup language:
A Example of plain text:
```
<tab-n>Hello this is my tab title lol</tab-n>
  <badgerTextProt>
    <bt>Hello this is plain text.</bt>
    // run a script
    <bs sor="test.bs"></bs>
    // ran a BadScript script
  </badgerTextProt>
```
**BADGER MARKUP WILL NOT WORK YET, ONLY THE BADGER PLAIN TEXT PROTOCAL IS SUPPORTED AT THE MOMENT**
A badscript script:
```
!client::badgium/opt
// Do !client::generic/opt if you are using a other browser from Badgium
// do comments with // like Go
var = "hello"
down $var
// Down is console.log pretty much
```
yes sir.
