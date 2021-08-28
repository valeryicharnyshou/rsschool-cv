# Valeryi Charnyshou

## Contacts

* Location: Nidda, Germany
* Phone, Telegram: +491703821239
* E-mail: vcharnyshou@icloud.com
* Skype: valerik.chernyshev
* GitHub: [GitHub](https://github.com/valeryicharnyshou)

## About

I am highly organized, responsive and flexible person. Started to work in IT in 2012
as a Technical support specialist. Since then gained experience in system administration,
networks configuration and DevOps. I am passionate about new technologies and tools,
learn quick and with pleasure. That's why i'm a student of RSSchool.

## Skills

* Server administration: Linux, DNS, DHCP, Web services, Virtualization and Monitoring
* Networks: experience of configuration L2 and L3 devices, routing and security
* DevOps: Docker, Ansible, K8s, Jenkins, AWS, GIT, Terraform

## Code examle

**Check if number is prime:**

```javascript
// program to check if a number is prime or not

// take input from the user
const number = parseInt(prompt("Enter a positive number: "));
let isPrime = true;

// check if number is equal to 1
if (number === 1) {
    console.log("1 is neither prime nor composite number.");
}

// check if number is greater than 1
else if (number > 1) {

    // looping through 2 to number-1
    for (let i = 2; i < number; i++) {
        if (number % i == 0) {
            isPrime = false;
            break;
        }
    }

    if (isPrime) {
        console.log(`${number} is a prime number`);
    } else {
        console.log(`${number} is a not prime number`);
    }
}

// check if number is less than 1
else {
    console.log("The number is not a prime number.");
}
```

## 
