# Function: <code>signalfd_copyinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int signalfd_copyinfo(struct signalfd_siginfo *uinfo, const siginfo_t *kinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff81257050)
Location: fs/signalfd.c:80
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff81257050-ffffffff81257313: signalfd_copyinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int signalfd_copyinfo(struct signalfd_siginfo *uinfo, const siginfo_t *kinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff8127f9a0)
Location: fs/signalfd.c:80
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff8127f9a0-ffffffff8127fc1f: signalfd_copyinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int signalfd_copyinfo(struct signalfd_siginfo *uinfo, const siginfo_t *kinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff81293510)
Location: fs/signalfd.c:80
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff81293510-ffffffff8129378f: signalfd_copyinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int signalfd_copyinfo(struct signalfd_siginfo *uinfo, const siginfo_t *kinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff812a07a0)
Location: fs/signalfd.c:80
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff812a07a0-ffffffff812a0a74: signalfd_copyinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int signalfd_copyinfo(struct signalfd_siginfo *uinfo, const siginfo_t *kinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff812c3b70)
Location: fs/signalfd.c:81
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff812c3b70-ffffffff812c3deb: signalfd_copyinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int signalfd_copyinfo(struct signalfd_siginfo *uinfo, const siginfo_t *kinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff812ecdf0)
Location: fs/signalfd.c:81
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff812ecdf0-ffffffff812ecf66: signalfd_copyinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int signalfd_copyinfo(struct signalfd_siginfo *uinfo, const kernel_siginfo_t *kinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff81301780)
Location: fs/signalfd.c:81
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff81301780-ffffffff81301920: signalfd_copyinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int signalfd_copyinfo(struct signalfd_siginfo *uinfo, const kernel_siginfo_t *kinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff81322cf0)
Location: fs/signalfd.c:81
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff81322cf0-ffffffff81322e86: signalfd_copyinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int signalfd_copyinfo(struct signalfd_siginfo *uinfo, const kernel_siginfo_t *kinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff81335a50)
Location: fs/signalfd.c:81
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff81335a50-ffffffff81335be6: signalfd_copyinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int signalfd_copyinfo(struct signalfd_siginfo *uinfo, const kernel_siginfo_t *kinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff8136f620)
Location: fs/signalfd.c:81
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff8136f620-ffffffff8136f7b6: signalfd_copyinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int signalfd_copyinfo(struct signalfd_siginfo *uinfo, const kernel_siginfo_t *kinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff8137d380)
Location: fs/signalfd.c:81
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff8137d380-ffffffff8137d516: signalfd_copyinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int signalfd_copyinfo(struct signalfd_siginfo *uinfo, const kernel_siginfo_t *kinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff81383fe0)
Location: fs/signalfd.c:81
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff81383fe0-ffffffff81384196: signalfd_copyinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int signalfd_copyinfo(struct signalfd_siginfo *uinfo, const kernel_siginfo_t *kinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff813d1280)
Location: fs/signalfd.c:71
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff813d1280-ffffffff813d1436: signalfd_copyinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int signalfd_copyinfo(struct signalfd_siginfo *uinfo, const kernel_siginfo_t *kinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff8145a5e0)
Location: fs/signalfd.c:71
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff8145a5e0-ffffffff8145a7a0: signalfd_copyinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int signalfd_copyinfo(struct signalfd_siginfo *uinfo, const kernel_siginfo_t *kinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff814e9b20)
Location: fs/signalfd.c:71
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff814e9b20-ffffffff814e9ce0: signalfd_copyinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int signalfd_copyinfo(struct signalfd_siginfo *uinfo, const kernel_siginfo_t *kinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff815208c0)
Location: fs/signalfd.c:71
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff815208c0-ffffffff81520a7e: signalfd_copyinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int signalfd_copyinfo(struct signalfd_siginfo *uinfo, const kernel_siginfo_t *kinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff81554ed0)
Location: fs/signalfd.c:71
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff81554ed0-ffffffff8155508e: signalfd_copyinfo (STB_LOCAL)
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
int signalfd_copyinfo(struct signalfd_siginfo *uinfo, const kernel_siginfo_t *kinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffff8000103f3b68)
Location: fs/signalfd.c:81
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffff8000103f3b68-ffff8000103f3ec0: signalfd_copyinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int signalfd_copyinfo(struct signalfd_siginfo *uinfo, const kernel_siginfo_t *kinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (c05c8b30)
Location: fs/signalfd.c:81
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
c05c8b30-c05c8d28: signalfd_copyinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int signalfd_copyinfo(struct signalfd_siginfo *uinfo, const kernel_siginfo_t *kinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (c0000000004fb270)
Location: fs/signalfd.c:81
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
c0000000004fb270-c0000000004fb48c: signalfd_copyinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int signalfd_copyinfo(struct signalfd_siginfo *uinfo, const kernel_siginfo_t *kinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffe0002a4e26)
Location: fs/signalfd.c:81
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffe0002a4e26-ffffffe0002a4f72: signalfd_copyinfo (STB_LOCAL)
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
int signalfd_copyinfo(struct signalfd_siginfo *uinfo, const kernel_siginfo_t *kinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff8132e030)
Location: fs/signalfd.c:81
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff8132e030-ffffffff8132e1c6: signalfd_copyinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int signalfd_copyinfo(struct signalfd_siginfo *uinfo, const kernel_siginfo_t *kinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff8131ec90)
Location: fs/signalfd.c:81
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff8131ec90-ffffffff8131ee26: signalfd_copyinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int signalfd_copyinfo(struct signalfd_siginfo *uinfo, const kernel_siginfo_t *kinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff8132bb00)
Location: fs/signalfd.c:81
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff8132bb00-ffffffff8132bc96: signalfd_copyinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int signalfd_copyinfo(struct signalfd_siginfo *uinfo, const kernel_siginfo_t *kinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/signalfd.c (ffffffff8133e560)
Location: fs/signalfd.c:81
Inline: False
Direct callers:
  - fs/signalfd.c:signalfd_read
```
**Symbols:**

```
ffffffff8133e560-ffffffff8133e6f6: signalfd_copyinfo (STB_LOCAL)
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
<b>Param type changed. </b>
<code>const siginfo_t *kinfo</code> ➡️ <code>const kernel_siginfo_t *kinfo</code>
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
