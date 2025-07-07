# RCE-NPM
A touch of security

## RCE? Postinstall?

Not your cup of tea?(mine too)

This Repo has Code to open Calculator Once when someone runs

```
npm install git+https://github.com/slvignesh05/RCE-NPM.git
```

Remote Code Execute Sire?

Yes.(RCE ya)

![rce](https://raw.githubusercontent.com/slvignesh05/RCE-NPM/refs/heads/main/public/images/Screenshot%202025-07-08%20000321.png)

## Package.json

```
"name":vul_name
"version":0.2.2
"scripts":{
     "postinstall": "node payload.js"
}
```

Here the `postinstall` triggers the code on payload.js to run malicious code(in this example to open Calculator)
