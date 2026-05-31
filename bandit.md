# Bandit Notes

[bandit link](https://overthewire.org/wargames/bandit/bandit5.html)

## Bandit 0

login

```shell
ssh -p 2220 bandit0@bandit.labs.overthewire.org
```

pass: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

---

## Bandit 1

command to solve

```shell
cat ./-
```

pass: 263JGJPfgU6LtdEvgfWU1XP5yac29mFx

---

## Bandit 2

```shell
cat ./'--spaces in this filename--'
```

pass: MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx

---

## Bandit 3

```shell
cd inhere
cat '...Hiding-From-You'
```

pass: 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ

---

## Bandit 4

```shell
cat ./-file07
```

pass: 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw

## Bandit 5

```shell
find . -size 1033c
cat ./maybehere07/.file2
```

pass: HWasnPhtq9AVKe0dmk45nxy20cvUa6EG

## bandit 6

```shell
find / -size 33c -group bandit6 -user bandit7 2> /dev/null
cat /var/lib/dpkg/info/bandit7.password
```

pass: morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj

## bandit 7

```shell
grep "millionth" data.txt
```

pass: dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc

## bandit 8

```shell
sort data.txt | uniq -u
```

pass: 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM

## bandit 9

```shell
strings data.txt | grep "="
```

pass: FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey

## bandit 10

```shell
base64 -d data.txt
```

pass: dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr

## bandit 11

```shell
cat data.txt | tr 'a-z' 'n-za-m' | tr 'A-Z' 'N-ZA-M'
```

pass: 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4

## bandit 12

```shell
cat data.txt | xxd -r > archive.gz
gzip -d archive.gz
mv archive archive.bz2
bzip2 -d archive.bz2
mv archive archive.tar
tar xf archive.tar
// repeat several times check teh file with the "file" command
```

pass: FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn

## bandit 13

no pass just get private key and use it for 14

```shell
cat /etc/bandit_pass/bandit14
```

pass: MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS

## bandit 14

```shell
echo "MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS" | nc localhost 30000 -t
```

pass: 8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo

## bandit 15

```shell

```

pass: 