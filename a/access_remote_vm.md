# Function: <code>access_remote_vm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, int write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811c1ea0)
Location: mm/memory.c:3729
Inline: False
Direct callers:
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
```
**Symbols:**

```
ffffffff811c1ea0-ffffffff811c1ec1: access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, int write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811dd9d0)
Location: mm/memory.c:3924
Inline: False
Direct callers:
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
```
**Symbols:**

```
ffffffff811dd9d0-ffffffff811dd9f1: access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ed8a0)
Location: mm/memory.c:4003
Inline: False
Direct callers:
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
```
**Symbols:**

```
ffffffff811ed8a0-ffffffff811ed8c1: access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f8850)
Location: mm/memory.c:4293
Inline: False
Direct callers:
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
```
**Symbols:**

```
ffffffff811f8850-ffffffff811f8871: access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81210a50)
Location: mm/memory.c:4471
Inline: False
Direct callers:
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
```
**Symbols:**

```
ffffffff81210a50-ffffffff81210a71: access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81231470)
Location: mm/memory.c:4519
Inline: False
Direct callers:
  - fs/proc/base.c:environ_read
```
**Symbols:**

```
ffffffff81231470-ffffffff81231491: access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81244c40)
Location: mm/memory.c:4309
Inline: False
Direct callers:
  - fs/proc/base.c:environ_read
```
**Symbols:**

```
ffffffff81244c40-ffffffff81244c61: access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81256c00)
Location: mm/memory.c:4364
Inline: False
Direct callers:
  - fs/proc/base.c:environ_read
```
**Symbols:**

```
ffffffff81256c00-ffffffff81256c25: access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81265190)
Location: mm/memory.c:4389
Inline: False
Direct callers:
  - fs/proc/base.c:environ_read
```
**Symbols:**

```
ffffffff81265190-ffffffff812651b5: access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81295560)
Location: mm/memory.c:4754
Inline: False
Direct callers:
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_cmdline
```
**Symbols:**

```
ffffffff81295560-ffffffff81295587: access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a0420)
Location: mm/memory.c:4981
Inline: False
Direct callers:
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_cmdline
```
**Symbols:**

```
ffffffff812a0420-ffffffff812a0430: access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a5d60)
Location: mm/memory.c:5048
Inline: False
Direct callers:
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_cmdline
```
**Symbols:**

```
ffffffff812a5d60-ffffffff812a5d70: access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e71f0)
Location: mm/memory.c:5194
Inline: False
Direct callers:
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_cmdline
```
**Symbols:**

```
ffffffff812e71f0-ffffffff812e7200: access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81348470)
Location: mm/memory.c:5501
Inline: False
Direct callers:
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_proctitle
```
**Symbols:**

```
ffffffff81348470-ffffffff8134848f: access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813c0910)
Location: mm/memory.c:5581
Inline: False
Direct callers:
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_proctitle
```
**Symbols:**

```
ffffffff813c0910-ffffffff813c092f: access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f5690)
Location: mm/memory.c:5787
Inline: False
Direct callers:
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_proctitle
```
**Symbols:**

```
ffffffff813f5690-ffffffff813f56af: access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141f370)
Location: mm/memory.c:6011
Inline: False
Direct callers:
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_cmdline
  - fs/proc/base.c:get_mm_proctitle
```
**Symbols:**

```
ffffffff8141f370-ffffffff8141f38f: access_remote_vm (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102fbb68)
Location: mm/memory.c:4389
Inline: False
Direct callers:
  - fs/proc/base.c:environ_read
```
**Symbols:**

```
ffff8000102fbb68-ffff8000102fbbc8: access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c051c234)
Location: mm/memory.c:4389
Inline: False
Direct callers:
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:mem_rw
  - fs/proc/base.c:mem_rw
```
**Symbols:**

```
c051c234-c051c278: access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c70a0)
Location: mm/memory.c:4389
Inline: False
Direct callers:
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:mem_rw
  - fs/proc/base.c:mem_rw
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_pid_cmdline_read
```
**Symbols:**

```
c0000000003c70a0-c0000000003c70dc: access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020b182)
Location: mm/memory.c:4389
Inline: False
Direct callers:
  - fs/proc/base.c:environ_read
  - fs/proc/base.c:mem_rw
  - fs/proc/base.c:mem_rw
```
**Symbols:**

```
ffffffe00020b182-ffffffe00020b1ce: access_remote_vm (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125d7e0)
Location: mm/memory.c:4389
Inline: False
Direct callers:
  - fs/proc/base.c:environ_read
```
**Symbols:**

```
ffffffff8125d7e0-ffffffff8125d805: access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124fc30)
Location: mm/memory.c:4389
Inline: False
Direct callers:
  - fs/proc/base.c:environ_read
```
**Symbols:**

```
ffffffff8124fc30-ffffffff8124fc55: access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125b580)
Location: mm/memory.c:4389
Inline: False
Direct callers:
  - fs/proc/base.c:environ_read
```
**Symbols:**

```
ffffffff8125b580-ffffffff8125b5a5: access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8126af60)
Location: mm/memory.c:4389
Inline: False
Direct callers:
  - fs/proc/base.c:environ_read
```
**Symbols:**

```
ffffffff8126af60-ffffffff8126af85: access_remote_vm (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int gup_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int write</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
