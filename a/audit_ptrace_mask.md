# Function: <code>audit_ptrace_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void audit_ptrace_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff81377b60)
Location: security/apparmor/ipc.c:30
Inline: True
Direct callers:
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
```
**Symbols:**

```
ffffffff81377b60-ffffffff81377bcb: audit_ptrace_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void audit_ptrace_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff813b0860)
Location: security/apparmor/ipc.c:30
Inline: True
Direct callers:
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
```
**Symbols:**

```
ffffffff813b0860-ffffffff813b08cb: audit_ptrace_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void audit_ptrace_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff813c79e0)
Location: security/apparmor/ipc.c:30
Inline: True
Direct callers:
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
```
**Symbols:**

```
ffffffff813c79e0-ffffffff813c7a4b: audit_ptrace_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void audit_ptrace_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff813dd380)
Location: security/apparmor/ipc.c:30
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
```
**Symbols:**

```
ffffffff813dd380-ffffffff813dd47f: audit_ptrace_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void audit_ptrace_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff81403eb0)
Location: security/apparmor/ipc.c:30
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
```
**Symbols:**

```
ffffffff81403eb0-ffffffff81403f1b: audit_ptrace_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void audit_ptrace_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff81434fa0)
Location: security/apparmor/ipc.c:30
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
```
**Symbols:**

```
ffffffff81434fa0-ffffffff8143500b: audit_ptrace_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void audit_ptrace_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff81451b90)
Location: security/apparmor/ipc.c:30
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
```
**Symbols:**

```
ffffffff81451b90-ffffffff81451bfb: audit_ptrace_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void audit_ptrace_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff8147f5a0)
Location: security/apparmor/ipc.c:26
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
```
**Symbols:**

```
ffffffff8147f5a0-ffffffff8147f60b: audit_ptrace_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void audit_ptrace_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff814992a0)
Location: security/apparmor/ipc.c:26
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
```
**Symbols:**

```
ffffffff814992a0-ffffffff8149930b: audit_ptrace_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void audit_ptrace_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff814f1800)
Location: security/apparmor/ipc.c:26
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
```
**Symbols:**

```
ffffffff814f1800-ffffffff814f186b: audit_ptrace_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff8150e95d)
Location: security/apparmor/ipc.c:27
Inline: True
Inline callers:
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff8151534d)
Location: security/apparmor/ipc.c:27
Inline: True
Inline callers:
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff815732fd)
Location: security/apparmor/ipc.c:27
Inline: True
Inline callers:
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
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
In security/apparmor/task.c (ffffffff8160fb2d)
Location: security/apparmor/task.c:192
Inline: True
Inline callers:
  - security/apparmor/task.c:audit_ptrace_cb
  - security/apparmor/task.c:audit_ptrace_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff816c2539)
Location: security/apparmor/task.c:192
Inline: True
Inline callers:
  - security/apparmor/task.c:audit_ptrace_cb
  - security/apparmor/task.c:audit_ptrace_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff816fb0e9)
Location: security/apparmor/task.c:192
Inline: True
Inline callers:
  - security/apparmor/task.c:audit_ptrace_cb
  - security/apparmor/task.c:audit_ptrace_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff81738019)
Location: security/apparmor/task.c:189
Inline: True
Inline callers:
  - security/apparmor/task.c:audit_ptrace_cb
  - security/apparmor/task.c:audit_ptrace_cb
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
void audit_ptrace_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffff80001058efa0)
Location: security/apparmor/ipc.c:26
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
```
**Symbols:**

```
ffff80001058efa0-ffff80001058f060: audit_ptrace_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void audit_ptrace_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (c073fe00)
Location: security/apparmor/ipc.c:26
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
```
**Symbols:**

```
c073fe00-c073feb0: audit_ptrace_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void audit_ptrace_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (c000000000701ff0)
Location: security/apparmor/ipc.c:26
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
```
**Symbols:**

```
c000000000701ff0-c0000000007020ec: audit_ptrace_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void audit_ptrace_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffe0003dcb32)
Location: security/apparmor/ipc.c:26
Inline: True
Direct callers:
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
```
**Symbols:**

```
ffffffe0003dcb32-ffffffe0003dcbe8: audit_ptrace_mask (STB_LOCAL)
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
void audit_ptrace_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff81491880)
Location: security/apparmor/ipc.c:26
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
```
**Symbols:**

```
ffffffff81491880-ffffffff814918eb: audit_ptrace_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void audit_ptrace_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff814822a0)
Location: security/apparmor/ipc.c:26
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
```
**Symbols:**

```
ffffffff814822a0-ffffffff8148230b: audit_ptrace_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void audit_ptrace_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff8148d920)
Location: security/apparmor/ipc.c:26
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
```
**Symbols:**

```
ffffffff8148d920-ffffffff8148d98b: audit_ptrace_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void audit_ptrace_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff814a5830)
Location: security/apparmor/ipc.c:26
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_ptrace_cb
  - security/apparmor/ipc.c:audit_ptrace_cb
```
**Symbols:**

```
ffffffff814a5830-ffffffff814a589b: audit_ptrace_mask (STB_LOCAL)
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
