- 👋 Hi, I’m @yashvantpatelzudo
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
yashvantpatelzudo/yashvantpatelzudo is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->I want to run cuffmerge as:  zudo@zudo:~$ cuffmerge -g /home/zudo/Desktop/bin/drosophila_21/refernce/genes.gtf -p 1 /home/zudo/Desktop/bin/drosophila_21/transcripts.txt
[Fri Aug 20 07:41:25 2021] Beginning transcriptome assembly merge
-------------------------------------------

[Fri Aug 20 07:41:25 2021] Preparing output location ./merged_asm/
Traceback (most recent call last):
  File "/usr/bin/cuffmerge", line 580, in <module>
    sys.exit(main())
  File "/usr/bin/cuffmerge", line 526, in main
    run_log = open(logging_dir + "run.log", "w", 0)
ValueError: can't have unbuffered text I/O
How would fix it?
