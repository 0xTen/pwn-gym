# pwn-gym
Personal goals/study guide

### Cover all linux kernel
- Finish LDD3: https://lwn.net/Kernel/LDD3/
- sk_buff:
  - https://blog.csdn.net/YuZhiHui_No1/article/details/38690015
  - https://blog.csdn.net/yuzhihui_no1/article/details/38737615
  - https://blog.csdn.net/YuZhiHui_No1/article/details/38827603
  - https://blog.csdn.net/YuZhiHui_No1/article/details/38965069
- setsockopt page spray:
  - https://googleprojectzero.blogspot.com/2017/05/exploiting-linux-kernel-via-packet.html
  - https://www.willsroot.io/2022/08/reviving-exploits-against-cred-struct.html
- msg_msg:
  - https://www.willsroot.io/2022/01/cve-2022-0185.html
  - https://www.willsroot.io/2021/08/corctf-2021-fire-of-salvation-writeup.html
- pipe_buffer:
  - https://0x434b.dev/learning-linux-kernel-exploitation-part-2-cve-2022-0847/
  - https://syst3mfailure.io/corjail
- dirty_cred:
  - https://i.blackhat.com/USA-22/Thursday/US-22-Lin-Cautious-A-New-Exploitation-Method.pdf
  - https://github.com/Markakd/DirtyCred/
- dirty_pipe:
  - https://0x434b.dev/learning-linux-kernel-exploitation-part-2-cve-2022-0847/
  - https://dirtypipe.cm4all.com/
- slab manipulation: https://www.personal.psu.edu/yxc431/publications/SLAKE.pdf
- slab objects reference: https://ptr-yudai.hatenablog.com/entry/2020/03/16/165628
- write exploits for all bugs from exploit recipes: https://drive.google.com/file/d/1kRHgQ9qDr4vgxJ4rVL-UNKvCamva_TRB/view

### KCTF setup
- undestand KCOV and write personal fuzzer:
  - https://blog.cloudflare.com/a-gentle-introduction-to-linux-kernel-fuzzing/
  - https://blog.trailofbits.com/2017/02/16/the-smart-fuzzer-revolution/
  - https://github.com/google/fuzzer-test-suite
  - http://lcamtuf.coredump.cx/afl/technical_details.txt
  - https://www.kernel.org/doc/html/v4.15/dev-tools/gcov.html
  - https://www.kernel.org/doc/html/latest/dev-tools/kcov.html
- write syzbot monitor + repro bot with GREBE:
  - https://zplin.me/papers/GREBE.pdf
  - https://github.com/Markakd/GREBE

- FINALLY GET KCTF BOUNTY: https://google.github.io/kctf/vrp.html
