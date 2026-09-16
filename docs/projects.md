# Projects

This page contains some of my educational projects completed during the Introduction in Web Technologies course.

## Laboratory Work 1 — Docker Basics

In this laboratory work, I learned the basics of Docker.

Main tasks included:

- Installing Docker
- Running the `hello-world` container
- Launching an Nginx web server
- Working with Docker images
- Managing containers
- Using Docker volumes

Example command:

```bash
docker run -d -p 8080:80 --name web-server nginx:alpine

Теперь:

```bash
cat > docs/contacts.md <<'EOF'
# Contacts

You can find my educational projects and coursework online.

## GitHub

My projects are available on GitHub.

## ITMO University

I am a student at **ITMO University**.

Official website:

[ITMO University](https://itmo.ru/)

## Course Information

| Field | Information |
| --- | --- |
| University | ITMO University |
| Course | Introduction in Web Technologies |
| Academic Year | 2026/2027 |

!!! note
    This website was created for educational purposes.
