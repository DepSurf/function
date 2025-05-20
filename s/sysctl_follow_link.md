# Function: <code>sysctl_follow_link</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sysctl_follow_link(struct ctl_table_header **phead, struct ctl_table **pentry, struct nsproxy *namespaces);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81284a20)
Location: fs/proc/proc_sysctl.c:979
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/proc/proc_sysctl.c:proc_sys_readdir
```
**Symbols:**

```
ffffffff81284a20-ffffffff81284b32: sysctl_follow_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sysctl_follow_link(struct ctl_table_header **phead, struct ctl_table **pentry, struct nsproxy *namespaces);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812b1af0)
Location: fs/proc/proc_sysctl.c:985
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff812b1af0-ffffffff812b1c02: sysctl_follow_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sysctl_follow_link(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812c7390)
Location: fs/proc/proc_sysctl.c:991
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff812c7390-ffffffff812c749c: sysctl_follow_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sysctl_follow_link(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812d46f0)
Location: fs/proc/proc_sysctl.c:1038
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff812d46f0-ffffffff812d47fc: sysctl_follow_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sysctl_follow_link(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812f8f20)
Location: fs/proc/proc_sysctl.c:1039
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff812f8f20-ffffffff812f902f: sysctl_follow_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sysctl_follow_link(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81325fe0)
Location: fs/proc/proc_sysctl.c:1041
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff81325fe0-ffffffff813260e8: sysctl_follow_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sysctl_follow_link(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8133d190)
Location: fs/proc/proc_sysctl.c:1040
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff8133d190-ffffffff8133d298: sysctl_follow_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sysctl_follow_link(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81365490)
Location: fs/proc/proc_sysctl.c:1065
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff81365490-ffffffff8136559c: sysctl_follow_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sysctl_follow_link(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8137d720)
Location: fs/proc/proc_sysctl.c:1065
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff8137d720-ffffffff8137d82c: sysctl_follow_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sysctl_follow_link(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813c7550)
Location: fs/proc/proc_sysctl.c:1048
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff813c7550-ffffffff813c765d: sysctl_follow_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sysctl_follow_link(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813d9540)
Location: fs/proc/proc_sysctl.c:1048
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff813d9540-ffffffff813d964d: sysctl_follow_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sysctl_follow_link(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813e0290)
Location: fs/proc/proc_sysctl.c:1046
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff813e0290-ffffffff813e039c: sysctl_follow_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sysctl_follow_link(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81431b30)
Location: fs/proc/proc_sysctl.c:1046
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff81431b30-ffffffff81431c3c: sysctl_follow_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sysctl_follow_link(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff814aba30)
Location: fs/proc/proc_sysctl.c:1070
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff814aba30-ffffffff814abb3d: sysctl_follow_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sysctl_follow_link(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81541ab0)
Location: fs/proc/proc_sysctl.c:1063
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff81541ab0-ffffffff81541bbd: sysctl_follow_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sysctl_follow_link(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81579db0)
Location: fs/proc/proc_sysctl.c:1056
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff81579db0-ffffffff81579ebd: sysctl_follow_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sysctl_follow_link(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815b26c0)
Location: fs/proc/proc_sysctl.c:1048
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff815b26c0-ffffffff815b27cd: sysctl_follow_link (STB_LOCAL)
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
int sysctl_follow_link(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffff80001044a438)
Location: fs/proc/proc_sysctl.c:1065
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffff80001044a438-ffff80001044a5a0: sysctl_follow_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sysctl_follow_link(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c060f04c)
Location: fs/proc/proc_sysctl.c:1065
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
c060f04c-c060f188: sysctl_follow_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sysctl_follow_link(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c000000000561780)
Location: fs/proc/proc_sysctl.c:1065
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
c000000000561780-c000000000561920: sysctl_follow_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sysctl_follow_link(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffe0002dfad4)
Location: fs/proc/proc_sysctl.c:1065
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffe0002dfad4-ffffffe0002dfbe4: sysctl_follow_link (STB_LOCAL)
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
int sysctl_follow_link(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81375d00)
Location: fs/proc/proc_sysctl.c:1065
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff81375d00-ffffffff81375e0c: sysctl_follow_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sysctl_follow_link(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813667d0)
Location: fs/proc/proc_sysctl.c:1065
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff813667d0-ffffffff813668dc: sysctl_follow_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sysctl_follow_link(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813737d0)
Location: fs/proc/proc_sysctl.c:1065
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff813737d0-ffffffff813738dc: sysctl_follow_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sysctl_follow_link(struct ctl_table_header **phead, struct ctl_table **pentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813872a0)
Location: fs/proc/proc_sysctl.c:1065
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_readdir
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff813872a0-ffffffff813873b0: sysctl_follow_link (STB_LOCAL)
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
<b>Param removed. </b>
<code>struct nsproxy *namespaces</code>
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
