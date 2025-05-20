# Function: <code>selinux_ptrace_access_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int selinux_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81346700)
Location: security/selinux/hooks.c:2061
Inline: True
```
**Symbols:**

```
ffffffff81346700-ffffffff81346753: selinux_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int selinux_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8137bcf0)
Location: security/selinux/hooks.c:2135
Inline: True
```
**Symbols:**

```
ffffffff8137bcf0-ffffffff8137bd43: selinux_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int selinux_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81392160)
Location: security/selinux/hooks.c:2143
Inline: True
```
**Symbols:**

```
ffffffff81392160-ffffffff813921b3: selinux_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int selinux_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a4840)
Location: security/selinux/hooks.c:2125
Inline: False
```
**Symbols:**

```
ffffffff813a4840-ffffffff813a48a8: selinux_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int selinux_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813ca910)
Location: security/selinux/hooks.c:2145
Inline: False
```
**Symbols:**

```
ffffffff813ca910-ffffffff813ca978: selinux_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int selinux_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813f9cd0)
Location: security/selinux/hooks.c:2266
Inline: False
```
**Symbols:**

```
ffffffff813f9cd0-ffffffff813f9d3c: selinux_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int selinux_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81415d90)
Location: security/selinux/hooks.c:2080
Inline: False
```
**Symbols:**

```
ffffffff81415d90-ffffffff81415e04: selinux_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int selinux_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814437c0)
Location: security/selinux/hooks.c:2124
Inline: False
```
**Symbols:**

```
ffffffff814437c0-ffffffff81443837: selinux_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int selinux_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145d310)
Location: security/selinux/hooks.c:2126
Inline: False
```
**Symbols:**

```
ffffffff8145d310-ffffffff8145d38f: selinux_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int selinux_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b0450)
Location: security/selinux/hooks.c:2079
Inline: False
```
**Symbols:**

```
ffffffff814b0450-ffffffff814b04cf: selinux_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int selinux_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d1180)
Location: security/selinux/hooks.c:2088
Inline: False
```
**Symbols:**

```
ffffffff814d1180-ffffffff814d121c: selinux_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int selinux_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d75d0)
Location: security/selinux/hooks.c:2141
Inline: False
```
**Symbols:**

```
ffffffff814d75d0-ffffffff814d766c: selinux_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int selinux_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81530320)
Location: security/selinux/hooks.c:2134
Inline: False
```
**Symbols:**

```
ffffffff81530320-ffffffff815303bc: selinux_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int selinux_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815c7330)
Location: security/selinux/hooks.c:2072
Inline: False
```
**Symbols:**

```
ffffffff815c7330-ffffffff815c73f9: selinux_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int selinux_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816741b0)
Location: security/selinux/hooks.c:2071
Inline: False
```
**Symbols:**

```
ffffffff816741b0-ffffffff81674279: selinux_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int selinux_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816ac410)
Location: security/selinux/hooks.c:2065
Inline: False
```
**Symbols:**

```
ffffffff816ac410-ffffffff816ac4c3: selinux_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int selinux_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816e9770)
Location: security/selinux/hooks.c:2105
Inline: False
```
**Symbols:**

```
ffffffff816e9770-ffffffff816e9829: selinux_ptrace_access_check (STB_LOCAL)
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
int selinux_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff80001054a140)
Location: security/selinux/hooks.c:2126
Inline: False
```
**Symbols:**

```
ffff80001054a140-ffff80001054a1d0: selinux_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int selinux_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c06fffac)
Location: security/selinux/hooks.c:2126
Inline: False
```
**Symbols:**

```
c06fffac-c0700040: selinux_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int selinux_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a19b0)
Location: security/selinux/hooks.c:2126
Inline: False
```
**Symbols:**

```
c0000000006a19b0-c0000000006a1a68: selinux_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int selinux_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a4d70)
Location: security/selinux/hooks.c:2126
Inline: False
```
**Symbols:**

```
ffffffe0003a4d70-ffffffe0003a4df2: selinux_ptrace_access_check (STB_LOCAL)
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
int selinux_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814558f0)
Location: security/selinux/hooks.c:2126
Inline: False
```
**Symbols:**

```
ffffffff814558f0-ffffffff8145596f: selinux_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int selinux_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81446330)
Location: security/selinux/hooks.c:2126
Inline: False
```
**Symbols:**

```
ffffffff81446330-ffffffff814463af: selinux_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int selinux_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81451990)
Location: security/selinux/hooks.c:2126
Inline: False
```
**Symbols:**

```
ffffffff81451990-ffffffff81451a0f: selinux_ptrace_access_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int selinux_ptrace_access_check(struct task_struct *child, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8146a260)
Location: security/selinux/hooks.c:2126
Inline: False
```
**Symbols:**

```
ffffffff8146a260-ffffffff8146a305: selinux_ptrace_access_check (STB_LOCAL)
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
