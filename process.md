process.md

process is an active entity
	program is an passive entity

process adalah 'program in execution'


program becomes process when executable file loaded into memory.
program menjadi process ketika file .exe di load ke memory.


# bentuk code nya
`
process_chrome = RAM.load(chrome_file.exe)
process_chrome.pid
`

dimana
pid =  process id


# state of process executes
1. New = di create
2. Ready 
tidak semua process berubah menjadi running
process menunggu utk dieksekusi di processor (CPU)
hal ini karena kapasitas CPU yang terbatas 

3. Running 
	lagi eksekusi until terminate/kill
	bisa di interrupt hingga berubah state menjadi ready

4. Waiting
	menunggu untuk mendapatkan event (onmouse, onkey, etc) atau menunggu data lain

5. Terminated
	distop oleh user


https://www.youtube.com/watch?v=ixGgJF7oaGI&t=128s

6:48 5 jenis state dari process
13:00 perbedaan thread vs process: 

proses adalah unit dari program yang di eksekusi
thread berada di dalam process
1 process memiliki beberapa thread. 
1 process minimal memiliki 1 thread, i.e main.


