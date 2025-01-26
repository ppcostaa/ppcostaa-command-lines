# Respostas para cada desafio 👩‍💻

## p1-B

- Comando utilizado: tar -xvzf challenges.tar.gz

## p2-B

- Comando utilizado: cd challenges

## p3-B

- Comando utilizado: ls

## p4-B

- Comando utilizado: mkdir foo

## p5-I

- Comando utilizado: mkdir -p foo/bar/1/2/3

## p6-B

- Comando utilizado: rm -rf foo

## p7-B

- Comando utilizado: echo "Hello World"

## p8-B

- Comando utilizado: echo "Hello World" > hello.txt

## p9-B

- Comando utilizado: touch empty.txt

## p10-B

- Comando utilizado: rm empty.txt

## p11-I

- Comando utilizado: > empty.txt

## p12-I

- Comando utilizado: echo "" > empty.txt

## p13-B

- Comando utilizado: cp hello.txt goodbye.txt

## p14-B

- Comando utilizado: mv goodbye.txt hello_copy.txt

## p15-I

- Comandos utilizados: cmp hello.txt hello_copy.txt
  e
  diff hello.txt hello_copy.txt
  Como não houve saída, significa que ambos são iguais.

## p16-B

- Comando utilizado: cat hello.txt hello_copy.txt > 2_hellos.txt

## p17-B

- Comando utilizado: pwd

## p18-B

- Comando utilizado: ls -l

## p19-B

- Comandos utilizados: echo "Texto adicional" > restricted.txt
  e
  echo "Texto extra" >> restricted.txt

## p20-B

- Comandos utilizados: chmod +x hello_executable
  e
  ./hello_executable

## p21-B

- Comandos utilizados: chmod +x challenge_20
  e
  ./challenge_20

## p22-B

- Comandos utilizados: gcc compile_me.c -o compile_me
  e
  ./compile_me

## p23-A

- Comandos utilizados: chmod +x redirect
  e
  ./redirect > output.txt

## p24-B

- Comando utilizado: date

## p25-B

- Comando utilizado: ps aux

## p26-B

- Comando utilizado: nproc

## p27-B

- Comando utilizado: uname -r

## p28-B

- Comando utilizado: grep -r "You found the needle in the haystack!" bunch_of_files/

## p29-B

- Comando utilizado: head -n 25 people.csv

## p30-B

- Comando utilizado: tail -n 25 people.csv

## p31-I

- Comando utilizado: diff greeting1.txt greeting2.txt

## p32-I

- Comando utilizado: echo "Hello"; sleep 5; echo "world!"

## p33-I

- Comando utilizado: dd if=/dev/zero of=file_1MB.txt bs=1M count=1

## p34-I

- Comando utilizado: dd if=/dev/urandom of=file_2MB.txt bs=1M count=2

## p35-I

- Comando utilizado: wc -l README.txt

## p36-B

- Comando utilizado: tac README.txt

## p37-I

- Comando utilizado: cut -d ',' -f 2 people.csv

## p38-A

- Comando utilizado: cut -d ',' -f 2 people.csv | sort | uniq | wc -l
