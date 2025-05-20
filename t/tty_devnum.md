# Function: <code>tty_devnum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
dev_t tty_devnum(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814df6a0)
Location: drivers/tty/tty_io.c:3559
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff814df6a0-ffffffff814df6bb: tty_devnum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
dev_t tty_devnum(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81534d45)
Location: drivers/tty/tty_io.c:3555
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81530770-ffffffff8153078b: tty_devnum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
dev_t tty_devnum(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81561475)
Location: drivers/tty/tty_io.c:3555
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff8155cec0-ffffffff8155cedb: tty_devnum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
dev_t tty_devnum(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8157505c)
Location: drivers/tty/tty_io.c:3108
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff815718d0-ffffffff815718eb: tty_devnum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
dev_t tty_devnum(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d984c)
Location: drivers/tty/tty_io.c:3215
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff815d5e30-ffffffff815d5e4b: tty_devnum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
dev_t tty_devnum(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816127d4)
Location: drivers/tty/tty_io.c:3236
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff8160ef70-ffffffff8160ef8b: tty_devnum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
dev_t tty_devnum(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162f874)
Location: drivers/tty/tty_io.c:3391
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff8162bb50-ffffffff8162bb6b: tty_devnum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
dev_t tty_devnum(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81663752)
Location: drivers/tty/tty_io.c:3395
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff8165fa80-ffffffff8165fa9b: tty_devnum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
dev_t tty_devnum(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81685dc2)
Location: drivers/tty/tty_io.c:3391
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff816820a0-ffffffff816820bb: tty_devnum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
dev_t tty_devnum(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81737833)
Location: drivers/tty/tty_io.c:3394
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - kernel/acct.c:fill_ac
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81733500-ffffffff8173351b: tty_devnum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
dev_t tty_devnum(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81753bf3)
Location: drivers/tty/tty_io.c:3487
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - kernel/acct.c:fill_ac
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff8174f660-ffffffff8174f67b: tty_devnum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
dev_t tty_devnum(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81737a93)
Location: drivers/tty/tty_io.c:3529
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - kernel/acct.c:fill_ac
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81733610-ffffffff8173362b: tty_devnum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
dev_t tty_devnum(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b852f)
Location: drivers/tty/tty_io.c:3516
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - kernel/acct.c:fill_ac
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff817b3f80-ffffffff817b3f9b: tty_devnum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
dev_t tty_devnum(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818f44a3)
Location: drivers/tty/tty_io.c:3495
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - kernel/acct.c:fill_ac
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff818efc00-ffffffff818efc23: tty_devnum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
dev_t tty_devnum(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a4cd0c)
Location: drivers/tty/tty_io.c:3492
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - kernel/acct.c:fill_ac
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81a47cd0-ffffffff81a47cf3: tty_devnum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
dev_t tty_devnum(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a96ffc)
Location: drivers/tty/tty_io.c:3498
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - kernel/acct.c:fill_ac
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81a91e70-ffffffff81a91e93: tty_devnum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
dev_t tty_devnum(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae9a1c)
Location: drivers/tty/tty_io.c:3515
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - kernel/acct.c:fill_ac
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81ae4850-ffffffff81ae4873: tty_devnum (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
dev_t tty_devnum(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff8000108537b8)
Location: drivers/tty/tty_io.c:3391
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffff80001084e3d0-ffff80001084e408: tty_devnum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
dev_t tty_devnum(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095e124)
Location: drivers/tty/tty_io.c:3391
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - kernel/acct.c:fill_ac
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
c095a348-c095a378: tty_devnum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
dev_t tty_devnum(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008f2b7c)
Location: drivers/tty/tty_io.c:3391
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
c0000000008ecb00-c0000000008ecb2c: tty_devnum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
dev_t tty_devnum(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe000530096)
Location: drivers/tty/tty_io.c:3391
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffe00052ca5e-ffffffe00052ca8e: tty_devnum (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
dev_t tty_devnum(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8164b842)
Location: drivers/tty/tty_io.c:3391
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81647b20-ffffffff81647b3b: tty_devnum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
dev_t tty_devnum(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162bc92)
Location: drivers/tty/tty_io.c:3391
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81627f80-ffffffff81627f9b: tty_devnum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
dev_t tty_devnum(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81679c02)
Location: drivers/tty/tty_io.c:3391
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81675ee0-ffffffff81675efb: tty_devnum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
dev_t tty_devnum(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81694262)
Location: drivers/tty/tty_io.c:3391
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:alloc_tty_struct
  - drivers/tty/tty_io.c:tty_ioctl
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81690540-ffffffff8169055b: tty_devnum (STB_GLOBAL)
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
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
