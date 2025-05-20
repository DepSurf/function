# Function: <code>send_sigio_to_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void send_sigio_to_task(struct task_struct *p, struct fown_struct *fown, int fd, int reason, int group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8121ec50)
Location: fs/fcntl.c:448
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio
```
**Symbols:**

```
ffffffff8121ec50-ffffffff8121ed8d: send_sigio_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void send_sigio_to_task(struct task_struct *p, struct fown_struct *fown, int fd, int reason, int group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812465e0)
Location: fs/fcntl.c:452
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio
```
**Symbols:**

```
ffffffff812465e0-ffffffff8124671d: send_sigio_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void send_sigio_to_task(struct task_struct *p, struct fown_struct *fown, int fd, int reason, int group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812595d0)
Location: fs/fcntl.c:452
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio
```
**Symbols:**

```
ffffffff812595d0-ffffffff8125970d: send_sigio_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void send_sigio_to_task(struct task_struct *p, struct fown_struct *fown, int fd, int reason, int group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812658d0)
Location: fs/fcntl.c:722
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio
```
**Symbols:**

```
ffffffff812658d0-ffffffff812659fe: send_sigio_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void send_sigio_to_task(struct task_struct *p, struct fown_struct *fown, int fd, int reason, int group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81288020)
Location: fs/fcntl.c:721
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio
```
**Symbols:**

```
ffffffff81288020-ffffffff81288155: send_sigio_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void send_sigio_to_task(struct task_struct *p, struct fown_struct *fown, int fd, int reason, int group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812ae350)
Location: fs/fcntl.c:727
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio
```
**Symbols:**

```
ffffffff812ae350-ffffffff812ae4a8: send_sigio_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void send_sigio_to_task(struct task_struct *p, struct fown_struct *fown, int fd, int reason, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812c3480)
Location: fs/fcntl.c:727
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
```
**Symbols:**

```
ffffffff812c3480-ffffffff812c35b6: send_sigio_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void send_sigio_to_task(struct task_struct *p, struct fown_struct *fown, int fd, int reason, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812dfe90)
Location: fs/fcntl.c:727
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
```
**Symbols:**

```
ffffffff812dfe90-ffffffff812dffd1: send_sigio_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void send_sigio_to_task(struct task_struct *p, struct fown_struct *fown, int fd, int reason, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812f1930)
Location: fs/fcntl.c:727
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
```
**Symbols:**

```
ffffffff812f1930-ffffffff812f1a71: send_sigio_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void send_sigio_to_task(struct task_struct *p, struct fown_struct *fown, int fd, int reason, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81329ad0)
Location: fs/fcntl.c:727
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
```
**Symbols:**

```
ffffffff81329ad0-ffffffff81329bf6: send_sigio_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void send_sigio_to_task(struct task_struct *p, struct fown_struct *fown, int fd, int reason, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81335030)
Location: fs/fcntl.c:727
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
```
**Symbols:**

```
ffffffff81335030-ffffffff81335160: send_sigio_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void send_sigio_to_task(struct task_struct *p, struct fown_struct *fown, int fd, int reason, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8133b1c0)
Location: fs/fcntl.c:732
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
```
**Symbols:**

```
ffffffff8133b1c0-ffffffff8133b2f0: send_sigio_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void send_sigio_to_task(struct task_struct *p, struct fown_struct *fown, int fd, int reason, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81388de0)
Location: fs/fcntl.c:736
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
```
**Symbols:**

```
ffffffff81388de0-ffffffff81388f2f: send_sigio_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void send_sigio_to_task(struct task_struct *p, struct fown_struct *fown, int fd, int reason, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8140a050)
Location: fs/fcntl.c:714
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
```
**Symbols:**

```
ffffffff8140a050-ffffffff8140a1c7: send_sigio_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void send_sigio_to_task(struct task_struct *p, struct fown_struct *fown, int fd, int reason, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81494970)
Location: fs/fcntl.c:715
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
```
**Symbols:**

```
ffffffff81494970-ffffffff81494ae7: send_sigio_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void send_sigio_to_task(struct task_struct *p, struct fown_struct *fown, int fd, int reason, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff814c99d0)
Location: fs/fcntl.c:716
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
```
**Symbols:**

```
ffffffff814c99d0-ffffffff814c9b47: send_sigio_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void send_sigio_to_task(struct task_struct *p, struct fown_struct *fown, int fd, int reason, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff814fc290)
Location: fs/fcntl.c:717
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
```
**Symbols:**

```
ffffffff814fc290-ffffffff814fc407: send_sigio_to_task (STB_LOCAL)
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
void send_sigio_to_task(struct task_struct *p, struct fown_struct *fown, int fd, int reason, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffff80001039b2b0)
Location: fs/fcntl.c:727
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
```
**Symbols:**

```
ffff80001039b2b0-ffff80001039b420: send_sigio_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void send_sigio_to_task(struct task_struct *p, struct fown_struct *fown, int fd, int reason, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (c0581848)
Location: fs/fcntl.c:727
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
```
**Symbols:**

```
c0581848-c05819b4: send_sigio_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void send_sigio_to_task(struct task_struct *p, struct fown_struct *fown, int fd, int reason, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (c000000000496650)
Location: fs/fcntl.c:727
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
```
**Symbols:**

```
c000000000496650-c000000000496884: send_sigio_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void send_sigio_to_task(struct task_struct *p, struct fown_struct *fown, int fd, int reason, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffe000268734)
Location: fs/fcntl.c:727
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
```
**Symbols:**

```
ffffffe000268734-ffffffe00026884e: send_sigio_to_task (STB_LOCAL)
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
void send_sigio_to_task(struct task_struct *p, struct fown_struct *fown, int fd, int reason, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812e9f10)
Location: fs/fcntl.c:727
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
```
**Symbols:**

```
ffffffff812e9f10-ffffffff812ea051: send_sigio_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void send_sigio_to_task(struct task_struct *p, struct fown_struct *fown, int fd, int reason, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812dacb0)
Location: fs/fcntl.c:727
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
```
**Symbols:**

```
ffffffff812dacb0-ffffffff812dadf1: send_sigio_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void send_sigio_to_task(struct task_struct *p, struct fown_struct *fown, int fd, int reason, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812e7d20)
Location: fs/fcntl.c:727
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
```
**Symbols:**

```
ffffffff812e7d20-ffffffff812e7e61: send_sigio_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void send_sigio_to_task(struct task_struct *p, struct fown_struct *fown, int fd, int reason, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812f8f80)
Location: fs/fcntl.c:727
Inline: False
Direct callers:
  - fs/fcntl.c:send_sigio
  - fs/fcntl.c:send_sigio
```
**Symbols:**

```
ffffffff812f8f80-ffffffff812f90d8: send_sigio_to_task (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum pid_type type</code>
</li>
<li>
<b>Param removed. </b>
<code>int group</code>
</li>
</ul>
</details>
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
