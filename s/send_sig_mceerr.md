# Function: <code>send_sig_mceerr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int send_sig_mceerr(int code, void *addr, short int lsb, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109f430)
Location: kernel/signal.c:1546
Inline: False
Direct callers:
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff8109f430-ffffffff8109f4c2: send_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int send_sig_mceerr(int code, void *addr, short int lsb, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a76f0)
Location: kernel/signal.c:1632
Inline: False
Direct callers:
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff810a76f0-ffffffff810a7776: send_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int send_sig_mceerr(int code, void *addr, short int lsb, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:1720
Inline: False
Direct callers:
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff810b0faf-ffffffff810b0fd2: send_sig_mceerr.cold (STB_LOCAL)
ffffffff810ade80-ffffffff810adf14: send_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int send_sig_mceerr(int code, void *addr, short int lsb, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b44a0)
Location: kernel/signal.c:1725
Inline: False
Direct callers:
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff810b44a0-ffffffff810b4526: send_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int send_sig_mceerr(int code, void *addr, short int lsb, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bc9e0)
Location: kernel/signal.c:1721
Inline: False
Direct callers:
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff810bc9e0-ffffffff810bca59: send_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int send_sig_mceerr(int code, void *addr, short int lsb, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b7cf0)
Location: kernel/signal.c:1722
Inline: False
Direct callers:
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff810b7cf0-ffffffff810b7d69: send_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int send_sig_mceerr(int code, void *addr, short int lsb, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b9250)
Location: kernel/signal.c:1724
Inline: False
Direct callers:
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff810b9250-ffffffff810b92c9: send_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int send_sig_mceerr(int code, void *addr, short int lsb, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cb7e0)
Location: kernel/signal.c:1761
Inline: False
Direct callers:
  - mm/memory-failure.c:kill_proc
```
**Symbols:**

```
ffffffff810cb7e0-ffffffff810cb859: send_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int send_sig_mceerr(int code, void *addr, short int lsb, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e27a0)
Location: kernel/signal.c:1762
Inline: False
Direct callers:
  - mm/memory-failure.c:kill_proc
```
**Symbols:**

```
ffffffff810e27a0-ffffffff810e283a: send_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int send_sig_mceerr(int code, void *addr, short int lsb, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81102bc0)
Location: kernel/signal.c:1763
Inline: False
Direct callers:
  - mm/memory-failure.c:kill_proc
```
**Symbols:**

```
ffffffff81102bc0-ffffffff81102c5a: send_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int send_sig_mceerr(int code, void *addr, short int lsb, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110ee00)
Location: kernel/signal.c:1769
Inline: False
Direct callers:
  - mm/memory-failure.c:kill_proc
```
**Symbols:**

```
ffffffff8110ee00-ffffffff8110ee9a: send_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int send_sig_mceerr(int code, void *addr, short int lsb, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81118780)
Location: kernel/signal.c:1760
Inline: False
Direct callers:
  - mm/memory-failure.c:kill_proc
```
**Symbols:**

```
ffffffff81118780-ffffffff8111881a: send_sig_mceerr (STB_GLOBAL)
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
int send_sig_mceerr(int code, void *addr, short int lsb, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff800010110528)
Location: kernel/signal.c:1725
Inline: False
Direct callers:
  - virt/kvm/arm/mmu.c:user_mem_abort
```
**Symbols:**

```
ffff800010110528-ffff8000101105e0: send_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int send_sig_mceerr(int code, void *addr, short int lsb, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0367ed4)
Location: kernel/signal.c:1725
Inline: False
```
**Symbols:**

```
c0367ed4-c0367f94: send_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int send_sig_mceerr(int code, void *addr, short int lsb, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000157c90)
Location: kernel/signal.c:1725
Inline: False
Direct callers:
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
c000000000157c90-c000000000157d3c: send_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int send_sig_mceerr(int code, void *addr, short int lsb, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d0406)
Location: kernel/signal.c:1725
Inline: False
```
**Symbols:**

```
ffffffe0000d0406-ffffffe0000d047a: send_sig_mceerr (STB_GLOBAL)
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
int send_sig_mceerr(int code, void *addr, short int lsb, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae810)
Location: kernel/signal.c:1725
Inline: False
Direct callers:
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff810ae810-ffffffff810ae896: send_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int send_sig_mceerr(int code, void *addr, short int lsb, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109d160)
Location: kernel/signal.c:1725
Inline: False
Direct callers:
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff8109d160-ffffffff8109d1e6: send_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int send_sig_mceerr(int code, void *addr, short int lsb, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810add70)
Location: kernel/signal.c:1725
Inline: False
Direct callers:
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff810add70-ffffffff810addf6: send_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int send_sig_mceerr(int code, void *addr, short int lsb, struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5fd0)
Location: kernel/signal.c:1725
Inline: False
Direct callers:
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff810b5fd0-ffffffff810b6056: send_sig_mceerr (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
