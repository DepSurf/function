# Function: <code>setfl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8121f057)
Location: fs/fcntl.c:32
Inline: True
Inline callers:
  - fs/fcntl.c:SyS_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int setfl(int fd, struct file *filp, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81246340)
Location: fs/fcntl.c:32
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff81246340-ffffffff81246498: setfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int setfl(int fd, struct file *filp, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81259340)
Location: fs/fcntl.c:32
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff81259340-ffffffff81259488: setfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int setfl(int fd, struct file *filp, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81265400)
Location: fs/fcntl.c:34
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff81265400-ffffffff81265561: setfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int setfl(int fd, struct file *filp, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81287cb0)
Location: fs/fcntl.c:35
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff81287cb0-ffffffff81287e1e: setfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int setfl(int fd, struct file *filp, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812ae630)
Location: fs/fcntl.c:35
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff812ae630-ffffffff812ae79e: setfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int setfl(int fd, struct file *filp, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812c3720)
Location: fs/fcntl.c:35
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff812c3720-ffffffff812c388e: setfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int setfl(int fd, struct file *filp, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812e0140)
Location: fs/fcntl.c:35
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff812e0140-ffffffff812e02ac: setfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int setfl(int fd, struct file *filp, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812f1be0)
Location: fs/fcntl.c:35
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff812f1be0-ffffffff812f1d4c: setfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int setfl(int fd, struct file *filp, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81329e50)
Location: fs/fcntl.c:35
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff81329e50-ffffffff81329fbb: setfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int setfl(int fd, struct file *filp, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff813353c0)
Location: fs/fcntl.c:35
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff813353c0-ffffffff8133552b: setfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int setfl(int fd, struct file *filp, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8133b490)
Location: fs/fcntl.c:36
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8133b490-ffffffff8133b5c7: setfl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int setfl(int fd, struct file *filp, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff813890d0)
Location: fs/fcntl.c:36
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff813890d0-ffffffff8138922d: setfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8140a378)
Location: fs/fcntl.c:36
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int setfl(int fd, struct file *filp, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff814947f0)
Location: fs/fcntl.c:36
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff814947f0-ffffffff81494958: setfl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int setfl(int fd, struct file *filp, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff814c9850)
Location: fs/fcntl.c:37
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff814c9850-ffffffff814c99c0: setfl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int setfl(int fd, struct file *filp, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff814fc100)
Location: fs/fcntl.c:37
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff814fc100-ffffffff814fc271: setfl (STB_LOCAL)
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
int setfl(int fd, struct file *filp, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffff80001039b608)
Location: fs/fcntl.c:35
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffff80001039b608-ffff80001039b78c: setfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int setfl(int fd, struct file *filp, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (c058152c)
Location: fs/fcntl.c:35
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
c058152c-c05816ac: setfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int setfl(int fd, struct file *filp, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (c000000000495ff0)
Location: fs/fcntl.c:35
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
c000000000495ff0-c000000000496210: setfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int setfl(int fd, struct file *filp, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffe00026884e)
Location: fs/fcntl.c:35
Inline: False
Direct callers:
  - fs/fcntl.c:__se_sys_fcntl
```
**Symbols:**

```
ffffffe00026884e-ffffffe000268992: setfl (STB_GLOBAL)
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
int setfl(int fd, struct file *filp, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812ea1c0)
Location: fs/fcntl.c:35
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff812ea1c0-ffffffff812ea32c: setfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int setfl(int fd, struct file *filp, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812dae00)
Location: fs/fcntl.c:35
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff812dae00-ffffffff812daf6c: setfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int setfl(int fd, struct file *filp, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812e7fd0)
Location: fs/fcntl.c:35
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff812e7fd0-ffffffff812e813c: setfl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int setfl(int fd, struct file *filp, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812f8b70)
Location: fs/fcntl.c:35
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff812f8b70-ffffffff812f8cd5: setfl (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int arg</code> ➡️ <code>unsigned int arg</code>
</li>
</ul>
</details>
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
