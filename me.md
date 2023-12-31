# Introduction  :notebook_with_decorative_cover:

Hello !

* I am shubhranshu Pattanaik 

> How can this be a name? Its just random letters jumbled together.

I also go by *Shub* (For anyone struggling to pronounce my name)

*   I Come from **Odisha**

## Where We Have :arrow_heading_down:

<img src="./images/2000_5e741e821a9ee.webp" width="400" height="400">  

##  :arrow_heading_down:


<img src="./images/Puri-Odisha-temple-India-background-Jagannatha.webp" width="400" height="200">  


##  :arrow_heading_down:


<img src="./images/magnet-valley-view-from.jpg" width="400" height="200"> 


## and this too :arrow_heading_down:


<img src="./images/36442626_2115263685394037_4487199930405879808_n.webp" width="400" height="400">  


* I am [21](https://you.regettingold.com/26/12/2001/) years old

* I have a [chipped tooth](https://www.orovalleydentalarts.com/facts-about-cracked-teeth/) :tooth:

* I mentally adapt to almost all kinds of situations fairly fast and have strong opinions on various topics, and am up for a good debate always.

* I am an intern at [A.P. Møller – Mærsk](https://www.maersk.com/about) (Danish: [ˈɛˀ ˈpʰe̝ˀ mølɐˈmɛɐ̯sk]), also known simply as Maersk (English: /mɛərsk/ MAIRSK)	:ship: working in the **Fbm DevOps and QE team** under **Sudhansu Mohanty**


# Tools DevOps Engineers often Use :hammer_and_wrench: 

## Docker
```
FROM node:18-alpine
WORKDIR /app
COPY . .
RUN yarn install --production
CMD ["node", "src/index.js"]
EXPOSE 3000
cd /path/to/getting-started-app
docker build -t getting-started .

```
_Code snippet to build a Dockerfile_ 

## Terraform
```
terraform {
  required_providers {
    aws = {
      source  = "hashicorp/aws"
      version = ">= 5.8.0"
    }
  }
  required_version = ">= 1.1.5"
}

variable "region" {
  description = "The AWS region your resources will be deployed"
}

provider "aws" {
  region = var.region
}

data "aws_ami" "ubuntu" {
  most_recent = true

  filter {
    name   = "name"
    values = ["ubuntu/images/hvm-ssd/ubuntu-focal-20.04-amd64-server-*"]
  }

  filter {
    name   = "virtualization-type"
    values = ["hvm"]
  }

  owners = ["099720109477"] # Canonical
}

resource "aws_instance" "example" {
  ami                    = data.aws_ami.ubuntu.id
  instance_type          = "t2.micro"
  vpc_security_group_ids = [aws_security_group.sg_8080.id]
  user_data              = <<-EOF
              #!/bin/bash
              apt-get update
              apt-get install -y apache2
              sed -i -e 's/80/8080/' /etc/apache2/ports.conf
              echo "Hello World" > /var/www/html/index.html
              systemctl restart apache2
              EOF
  tags = {
    Name = "terraform-learn-state-ec2"
  }
}
```
*Snippet from a terraform statefile*

## And a whole lot more!

# What Maersk does: :world_map: 

[![What Maersk Does](./images/download.jpeg)](https://www.youtube.com/watch?v=I8F7GZnERNU)                                   
                                                  

____________________________________________________________


# Where Maersk Stands: :electron:

[![Where Maersk Stands](./images/cross-border-rail-transportation_720x405.webp)](https://www.youtube.com/watch?v=4GixY3P9mfs)  



_____________________________________________________________



# Some Facts on A.P. Moller Maersk 	:ship:

A.P. Møller – Mærsk A/S (Danish: [ˈɛˀ ˈpʰe̝ˀ mølɐˈmɛɐ̯sk]), also known simply as Maersk (English: /mɛərsk/ MAIRSK), is a Danish shipping and logistics company founded in 1904 by Peter Mærsk Møller and Arnold Peter Møller.

* Founded:	16 April 1904; 119 years ago, Svendborg, Denmark
* Founders:	**Arnold Peter Møller** and **Peter Mærsk Møller**
* Headquarters:	Copenhagen, Denmark 
* Vincent Clerc (CEO)
* Revenue:	US$81.5 billion (2022)
* Operating income:	US$29.7 billion (2022)
* Net income:	US$29.3 billion (2022)
* Total assets:	US$93.7 billion (2022)
* Total equity:	US$65 billion (2022)
* Number of employees:	104,260 (2022)
* Subsidiaries:	900+



# Controversial Opinions I Have:

<details>
<summary><strong>1. Terminator(1984) is a Sci-Fi Horror Movie</strong></summary>


This Scene Right here &rarr; ![Ill be back](./images/ill-be-back-terminator.gif)


and This Image &darr; should be enough to prove my point

![T800](./images/download%20(1).jpeg)

</details>

---
<details>
<summary>2. Continental GT-650 has an overcommitted and very unconfortable riding posture</summary>



**How can this be Comfortable!!**

![posture](./images/66708307.jpg)



</details>

---
<details>
<summary>3. Roger Moore was the worst james bond </summary>



This is supposed to be [Roger Moore](https://en.wikipedia.org/wiki/Roger_Moore) in The 1985 Bond movie _A View To Kill_ :magic_wand:


![rm](./images/rm%20stunt.jpeg)



</details>


---

<details>
<summary>3. You need to have basic understanding of quantum physics for _Enhanced_ Viewing of any **Christopher Nolan** Movie </summary>

**Anybody who has seen**

1. Interstellar
2. Tenet
3. Oppenheimer 

**can attest to this**



</details>

## Reach me

| Where | How |
|----------|---------|
|Email  | shubhranshu.pattanaik@maersk.com
|LinkedIn| [Shubhranshu Linkedin](https://www.linkedin.com/in/shubhranshu-pattanaik-12ty/)
|Whatsapp| +91-7735406476|

![finish](./images/finish-icon.svg)
