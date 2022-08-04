## SSH KEY

#### Create a new key

1. ssh-keygen -t rsa -b 4096 -C "My email"

2. ls | grep nameKey (this shows) ->
    * Private key
    * Public key

3. show to git that you are the owner
    - eval $(ssh-agent -s)
    - ssh-add ~/.ssh/keyName

4. cat namekey.pub (it shows key) and with pbcopy/copy < ~/.ssh/keyName.pub we copy the key

