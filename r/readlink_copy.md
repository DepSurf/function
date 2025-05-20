# Function: <code>readlink_copy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int readlink_copy(char *buffer, int buflen, const char *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81216910)
Location: fs/namei.c:4488
Inline: False
Direct callers:
  - fs/namei.c:generic_readlink
  - fs/namei.c:page_readlink
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/self.c:proc_self_readlink
  - fs/proc/thread_self.c:proc_thread_self_readlink
```
**Symbols:**

```
ffffffff81216910-ffffffff8121695f: readlink_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int readlink_copy(char *buffer, int buflen, const char *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812461b0)
Location: fs/namei.c:4642
Inline: False
Direct callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:generic_readlink
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/self.c:proc_self_readlink
  - fs/proc/thread_self.c:proc_thread_self_readlink
```
**Symbols:**

```
ffffffff812461b0-ffffffff81246218: readlink_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int readlink_copy(char *buffer, int buflen, const char *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81259130)
Location: fs/namei.c:4586
Inline: False
Direct callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/proc/namespaces.c:proc_ns_readlink
```
**Symbols:**

```
ffffffff81259130-ffffffff81259198: readlink_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int readlink_copy(char *buffer, int buflen, const char *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81265200)
Location: fs/namei.c:4652
Inline: False
Direct callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/proc/namespaces.c:proc_ns_readlink
  - security/apparmor/apparmorfs.c:policy_readlink
```
**Symbols:**

```
ffffffff81265200-ffffffff81265267: readlink_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int readlink_copy(char *buffer, int buflen, const char *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81287aa0)
Location: fs/namei.c:4648
Inline: False
Direct callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/proc/namespaces.c:proc_ns_readlink
  - security/apparmor/apparmorfs.c:policy_readlink
```
**Symbols:**

```
ffffffff81287aa0-ffffffff81287b07: readlink_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int readlink_copy(char *buffer, int buflen, const char *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812a6082)
Location: fs/namei.c:4700
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
Direct callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/proc/namespaces.c:proc_ns_readlink
  - security/apparmor/apparmorfs.c:policy_readlink
```
**Symbols:**

```
ffffffff812a5fe0-ffffffff812a603c: readlink_copy.part.64 (STB_LOCAL)
ffffffff812ae230-ffffffff812ae24c: readlink_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int readlink_copy(char *buffer, int buflen, const char *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812bb1f2)
Location: fs/namei.c:4689
Inline: True
Inline callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
Direct callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/proc/namespaces.c:proc_ns_readlink
  - security/apparmor/apparmorfs.c:policy_readlink
```
**Symbols:**

```
ffffffff812bb150-ffffffff812bb1ac: readlink_copy.part.65 (STB_LOCAL)
ffffffff812c3340-ffffffff812c335c: readlink_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int readlink_copy(char *buffer, int buflen, const char *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dfab0)
Location: fs/namei.c:4690
Inline: False
Direct callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/proc/namespaces.c:proc_ns_readlink
  - security/apparmor/apparmorfs.c:policy_readlink
```
**Symbols:**

```
ffffffff812dfab0-ffffffff812dfb1f: readlink_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int readlink_copy(char *buffer, int buflen, const char *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f15c0)
Location: fs/namei.c:4685
Inline: False
Direct callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/proc/namespaces.c:proc_ns_readlink
  - security/apparmor/apparmorfs.c:policy_readlink
```
**Symbols:**

```
ffffffff812f15c0-ffffffff812f1642: readlink_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int readlink_copy(char *buffer, int buflen, const char *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81329860)
Location: fs/namei.c:4499
Inline: False
Direct callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/proc/namespaces.c:proc_ns_readlink
  - security/apparmor/apparmorfs.c:policy_readlink
```
**Symbols:**

```
ffffffff81329860-ffffffff813298e2: readlink_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int readlink_copy(char *buffer, int buflen, const char *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81334dc0)
Location: fs/namei.c:4503
Inline: False
Direct callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/proc/namespaces.c:proc_ns_readlink
  - security/apparmor/apparmorfs.c:policy_readlink
```
**Symbols:**

```
ffffffff81334dc0-ffffffff81334e42: readlink_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int readlink_copy(char *buffer, int buflen, const char *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8133af50)
Location: fs/namei.c:4749
Inline: False
Direct callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/proc/namespaces.c:proc_ns_readlink
  - security/apparmor/apparmorfs.c:policy_readlink
```
**Symbols:**

```
ffffffff8133af50-ffffffff8133afd2: readlink_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int readlink_copy(char *buffer, int buflen, const char *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81388b70)
Location: fs/namei.c:4829
Inline: False
Direct callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/proc/namespaces.c:proc_ns_readlink
  - security/apparmor/apparmorfs.c:policy_readlink
```
**Symbols:**

```
ffffffff81388b70-ffffffff81388bf2: readlink_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int readlink_copy(char *buffer, int buflen, const char *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81409c00)
Location: fs/namei.c:4924
Inline: False
Direct callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/proc/namespaces.c:proc_ns_readlink
  - security/apparmor/apparmorfs.c:policy_readlink
```
**Symbols:**

```
ffffffff81409c00-ffffffff81409c7d: readlink_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int readlink_copy(char *buffer, int buflen, const char *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81494330)
Location: fs/namei.c:4980
Inline: False
Direct callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/proc/namespaces.c:proc_ns_readlink
  - security/apparmor/apparmorfs.c:policy_readlink
```
**Symbols:**

```
ffffffff81494330-ffffffff814943ad: readlink_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int readlink_copy(char *buffer, int buflen, const char *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c93a0)
Location: fs/namei.c:5059
Inline: False
Direct callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/proc/namespaces.c:proc_ns_readlink
  - security/apparmor/apparmorfs.c:policy_readlink
```
**Symbols:**

```
ffffffff814c93a0-ffffffff814c941d: readlink_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int readlink_copy(char *buffer, int buflen, const char *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814fbc60)
Location: fs/namei.c:5091
Inline: False
Direct callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/proc/namespaces.c:proc_ns_readlink
  - security/apparmor/apparmorfs.c:policy_readlink
```
**Symbols:**

```
ffffffff814fbc60-ffffffff814fbcdd: readlink_copy (STB_GLOBAL)
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
int readlink_copy(char *buffer, int buflen, const char *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff80001039aca8)
Location: fs/namei.c:4685
Inline: False
Direct callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/proc/namespaces.c:proc_ns_readlink
  - security/apparmor/apparmorfs.c:policy_readlink
```
**Symbols:**

```
ffff80001039aca8-ffff80001039ae90: readlink_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int readlink_copy(char *buffer, int buflen, const char *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c05811ec)
Location: fs/namei.c:4685
Inline: False
Direct callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/proc/namespaces.c:proc_ns_readlink
  - security/apparmor/apparmorfs.c:policy_readlink
```
**Symbols:**

```
c05811ec-c05812f4: readlink_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int readlink_copy(char *buffer, int buflen, const char *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000495c10)
Location: fs/namei.c:4685
Inline: False
Direct callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/proc/namespaces.c:proc_ns_readlink
  - security/apparmor/apparmorfs.c:policy_readlink
```
**Symbols:**

```
c000000000495c10-c000000000495d0c: readlink_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int readlink_copy(char *buffer, int buflen, const char *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe0002683b2)
Location: fs/namei.c:4685
Inline: False
Direct callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/proc/namespaces.c:proc_ns_readlink
  - security/apparmor/apparmorfs.c:policy_readlink
```
**Symbols:**

```
ffffffe0002683b2-ffffffe000268444: readlink_copy (STB_GLOBAL)
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
int readlink_copy(char *buffer, int buflen, const char *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e9ba0)
Location: fs/namei.c:4685
Inline: False
Direct callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/proc/namespaces.c:proc_ns_readlink
  - security/apparmor/apparmorfs.c:policy_readlink
```
**Symbols:**

```
ffffffff812e9ba0-ffffffff812e9c22: readlink_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int readlink_copy(char *buffer, int buflen, const char *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812da7e0)
Location: fs/namei.c:4685
Inline: False
Direct callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/proc/namespaces.c:proc_ns_readlink
  - security/apparmor/apparmorfs.c:policy_readlink
```
**Symbols:**

```
ffffffff812da7e0-ffffffff812da862: readlink_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int readlink_copy(char *buffer, int buflen, const char *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e79b0)
Location: fs/namei.c:4685
Inline: False
Direct callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/proc/namespaces.c:proc_ns_readlink
  - security/apparmor/apparmorfs.c:policy_readlink
```
**Symbols:**

```
ffffffff812e79b0-ffffffff812e7a32: readlink_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int readlink_copy(char *buffer, int buflen, const char *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f8930)
Location: fs/namei.c:4685
Inline: False
Direct callers:
  - fs/namei.c:page_readlink
  - fs/namei.c:vfs_readlink
  - fs/proc/namespaces.c:proc_ns_readlink
  - security/apparmor/apparmorfs.c:policy_readlink
```
**Symbols:**

```
ffffffff812f8930-ffffffff812f89b2: readlink_copy (STB_GLOBAL)
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
