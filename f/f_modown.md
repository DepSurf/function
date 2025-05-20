# Function: <code>f_modown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void f_modown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8121eb10)
Location: fs/fcntl.c:83
Inline: False
Direct callers:
  - fs/fcntl.c:f_setown
  - fs/fcntl.c:f_delown
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff8121eb10-ffffffff8121ebaf: f_modown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void f_modown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812464a0)
Location: fs/fcntl.c:87
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
  - fs/fcntl.c:f_delown
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff812464a0-ffffffff8124653f: f_modown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void f_modown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81259490)
Location: fs/fcntl.c:87
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
  - fs/fcntl.c:f_delown
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff81259490-ffffffff81259526: f_modown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void f_modown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81265570)
Location: fs/fcntl.c:89
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_delown
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff81265570-ffffffff81265606: f_modown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void f_modown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812882ed)
Location: fs/fcntl.c:90
Inline: True
Inline callers:
  - fs/fcntl.c:f_delown
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff81288180-ffffffff81288216: f_modown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void f_modown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812ae4d0)
Location: fs/fcntl.c:90
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_delown
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff812ae4d0-ffffffff812ae566: f_modown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void f_modown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812c35c0)
Location: fs/fcntl.c:90
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_delown
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff812c35c0-ffffffff812c3656: f_modown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void f_modown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812dffe0)
Location: fs/fcntl.c:90
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_delown
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff812dffe0-ffffffff812e007c: f_modown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void f_modown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812f1a80)
Location: fs/fcntl.c:90
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_delown
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff812f1a80-ffffffff812f1b1c: f_modown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void f_modown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81329fc5)
Location: fs/fcntl.c:90
Inline: True
Inline callers:
  - fs/fcntl.c:f_delown
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff81329cc0-ffffffff81329d85: f_modown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void f_modown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81335535)
Location: fs/fcntl.c:90
Inline: True
Inline callers:
  - fs/fcntl.c:f_delown
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff81335220-ffffffff813352e5: f_modown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void f_modown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8133b5d5)
Location: fs/fcntl.c:88
Inline: True
Inline callers:
  - fs/fcntl.c:f_delown
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff8133b2f0-ffffffff8133b3b5: f_modown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void f_modown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81389235)
Location: fs/fcntl.c:91
Inline: True
Inline callers:
  - fs/fcntl.c:f_delown
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff81388f30-ffffffff81388ff5: f_modown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void f_modown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8140a1d5)
Location: fs/fcntl.c:87
Inline: True
Inline callers:
  - fs/fcntl.c:f_delown
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff81409e70-ffffffff81409f4a: f_modown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void f_modown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81494b05)
Location: fs/fcntl.c:88
Inline: True
Inline callers:
  - fs/fcntl.c:f_delown
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff814945e0-ffffffff814946ba: f_modown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void f_modown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff814c9b65)
Location: fs/fcntl.c:89
Inline: True
Inline callers:
  - fs/fcntl.c:f_delown
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff814c9650-ffffffff814c971b: f_modown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void f_modown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff814fc425)
Location: fs/fcntl.c:89
Inline: True
Inline callers:
  - fs/fcntl.c:f_delown
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff814fbf10-ffffffff814fbfdb: f_modown (STB_LOCAL)
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
void f_modown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffff80001039b420)
Location: fs/fcntl.c:90
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_delown
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffff80001039b420-ffff80001039b510: f_modown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void f_modown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (c05816ac)
Location: fs/fcntl.c:90
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_delown
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
c05816ac-c0581758: f_modown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void f_modown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (c000000000496210)
Location: fs/fcntl.c:90
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_delown
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
c000000000496210-c000000000496370: f_modown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void f_modown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffe0002685a8)
Location: fs/fcntl.c:90
Inline: False
Direct callers:
  - fs/fcntl.c:__se_sys_fcntl
  - fs/fcntl.c:f_delown
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffe0002685a8-ffffffe000268630: f_modown (STB_LOCAL)
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
void f_modown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812ea060)
Location: fs/fcntl.c:90
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_delown
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff812ea060-ffffffff812ea0fc: f_modown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void f_modown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812daa30)
Location: fs/fcntl.c:90
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_delown
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff812daa30-ffffffff812daac6: f_modown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void f_modown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812e7e70)
Location: fs/fcntl.c:90
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_delown
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff812e7e70-ffffffff812e7f0c: f_modown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void f_modown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812f8ce0)
Location: fs/fcntl.c:90
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_delown
  - fs/fcntl.c:f_setown
```
**Symbols:**

```
ffffffff812f8ce0-ffffffff812f8d80: f_modown (STB_LOCAL)
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
