# Function: <code>audit_signal_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void audit_signal_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff81377c80)
Location: security/apparmor/ipc.c:140
Inline: True
Direct callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
```
**Symbols:**

```
ffffffff81377c80-ffffffff81377cc7: audit_signal_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void audit_signal_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff813b0980)
Location: security/apparmor/ipc.c:140
Inline: True
Direct callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
```
**Symbols:**

```
ffffffff813b0980-ffffffff813b09c7: audit_signal_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void audit_signal_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff813c7b00)
Location: security/apparmor/ipc.c:140
Inline: True
Direct callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
```
**Symbols:**

```
ffffffff813c7b00-ffffffff813c7b47: audit_signal_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void audit_signal_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff813dd1f0)
Location: security/apparmor/ipc.c:141
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
```
**Symbols:**

```
ffffffff813dd1f0-ffffffff813dd285: audit_signal_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void audit_signal_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff81403d50)
Location: security/apparmor/ipc.c:152
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
```
**Symbols:**

```
ffffffff81403d50-ffffffff81403d97: audit_signal_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void audit_signal_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff81434e50)
Location: security/apparmor/ipc.c:152
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
```
**Symbols:**

```
ffffffff81434e50-ffffffff81434e9f: audit_signal_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void audit_signal_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff81451a40)
Location: security/apparmor/ipc.c:153
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
```
**Symbols:**

```
ffffffff81451a40-ffffffff81451a8f: audit_signal_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void audit_signal_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff8147f450)
Location: security/apparmor/ipc.c:149
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
```
**Symbols:**

```
ffffffff8147f450-ffffffff8147f49f: audit_signal_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void audit_signal_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff81499150)
Location: security/apparmor/ipc.c:149
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
```
**Symbols:**

```
ffffffff81499150-ffffffff8149919f: audit_signal_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff814f19e8)
Location: security/apparmor/ipc.c:149
Inline: True
Inline callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
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
In security/apparmor/ipc.c (ffffffff8150ea2e)
Location: security/apparmor/ipc.c:148
Inline: True
Inline callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
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
In security/apparmor/ipc.c (ffffffff8151541e)
Location: security/apparmor/ipc.c:148
Inline: True
Inline callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
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
In security/apparmor/ipc.c (ffffffff815733d2)
Location: security/apparmor/ipc.c:148
Inline: True
Inline callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
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
In security/apparmor/ipc.c (ffffffff81610a12)
Location: security/apparmor/ipc.c:41
Inline: True
Inline callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
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
In security/apparmor/ipc.c (ffffffff816c346d)
Location: security/apparmor/ipc.c:41
Inline: True
Inline callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
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
In security/apparmor/ipc.c (ffffffff816fc04d)
Location: security/apparmor/ipc.c:41
Inline: True
Inline callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
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
In security/apparmor/ipc.c (ffffffff817395ad)
Location: security/apparmor/ipc.c:41
Inline: True
Inline callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
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
void audit_signal_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffff80001058ee10)
Location: security/apparmor/ipc.c:149
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
```
**Symbols:**

```
ffff80001058ee10-ffff80001058ee78: audit_signal_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void audit_signal_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (c073fc78)
Location: security/apparmor/ipc.c:149
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
```
**Symbols:**

```
c073fc78-c073fcd8: audit_signal_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void audit_signal_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (c000000000701db0)
Location: security/apparmor/ipc.c:149
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
```
**Symbols:**

```
c000000000701db0-c000000000701e64: audit_signal_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void audit_signal_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffe0003dcc9e)
Location: security/apparmor/ipc.c:149
Inline: True
Direct callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
```
**Symbols:**

```
ffffffe0003dcc9e-ffffffe0003dcd06: audit_signal_mask (STB_LOCAL)
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
void audit_signal_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff81491730)
Location: security/apparmor/ipc.c:149
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
```
**Symbols:**

```
ffffffff81491730-ffffffff8149177f: audit_signal_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void audit_signal_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff81482150)
Location: security/apparmor/ipc.c:149
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
```
**Symbols:**

```
ffffffff81482150-ffffffff8148219f: audit_signal_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void audit_signal_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff8148d7d0)
Location: security/apparmor/ipc.c:149
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
```
**Symbols:**

```
ffffffff8148d7d0-ffffffff8148d81f: audit_signal_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void audit_signal_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/ipc.c (ffffffff814a56e0)
Location: security/apparmor/ipc.c:149
Inline: False
Direct callers:
  - security/apparmor/ipc.c:audit_signal_cb
  - security/apparmor/ipc.c:audit_signal_cb
```
**Symbols:**

```
ffffffff814a56e0-ffffffff814a572f: audit_signal_mask (STB_LOCAL)
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
