# Function: <code>audit_file_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void audit_file_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff81387960)
Location: security/apparmor/file.c:45
Inline: False
Direct callers:
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
```
**Symbols:**

```
ffffffff81387960-ffffffff813879e7: audit_file_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void audit_file_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff813c2420)
Location: security/apparmor/file.c:45
Inline: False
Direct callers:
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
```
**Symbols:**

```
ffffffff813c2420-ffffffff813c24a7: audit_file_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void audit_file_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff813d98c0)
Location: security/apparmor/file.c:45
Inline: False
Direct callers:
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
```
**Symbols:**

```
ffffffff813d98c0-ffffffff813d9947: audit_file_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void audit_file_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff813eaa80)
Location: security/apparmor/file.c:47
Inline: False
Direct callers:
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
```
**Symbols:**

```
ffffffff813eaa80-ffffffff813eab2c: audit_file_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void audit_file_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffff814123b0)
Location: security/apparmor/file.c:47
Inline: False
Direct callers:
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
```
**Symbols:**

```
ffffffff814123b0-ffffffff8141245c: audit_file_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void audit_file_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/file.c (0)
Location: security/apparmor/file.c:47
Inline: False
Direct callers:
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
```
**Symbols:**

```
ffffffff81444760-ffffffff814447fc: audit_file_mask (STB_LOCAL)
ffffffff81445aff-ffffffff81445b17: audit_file_mask.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void audit_file_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/file.c (0)
Location: security/apparmor/file.c:47
Inline: False
Direct callers:
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
```
**Symbols:**

```
ffffffff81461630-ffffffff814616d1: audit_file_mask (STB_LOCAL)
ffffffff81462a1a-ffffffff81462a32: audit_file_mask.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void audit_file_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/file.c (0)
Location: security/apparmor/file.c:43
Inline: False
Direct callers:
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
```
**Symbols:**

```
ffffffff8148e900-ffffffff8148e9a3: audit_file_mask (STB_LOCAL)
ffffffff8148fccd-ffffffff8148fce5: audit_file_mask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void audit_file_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/file.c (0)
Location: security/apparmor/file.c:43
Inline: False
Direct callers:
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
```
**Symbols:**

```
ffffffff814a87c0-ffffffff814a8863: audit_file_mask (STB_LOCAL)
ffffffff814a9b8d-ffffffff814a9ba5: audit_file_mask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void audit_file_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/file.c (0)
Location: security/apparmor/file.c:43
Inline: False
Direct callers:
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
```
**Symbols:**

```
ffffffff81505da0-ffffffff81505e41: audit_file_mask (STB_LOCAL)
ffffffff8150752f-ffffffff81507547: audit_file_mask.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void audit_file_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffff80001059efd0)
Location: security/apparmor/file.c:43
Inline: False
Direct callers:
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
```
**Symbols:**

```
ffff80001059efd0-ffff80001059f0a0: audit_file_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void audit_file_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (c074fcb4)
Location: security/apparmor/file.c:43
Inline: False
Direct callers:
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
```
**Symbols:**

```
c074fcb4-c074fd78: audit_file_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void audit_file_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (c000000000718c60)
Location: security/apparmor/file.c:43
Inline: False
Direct callers:
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
```
**Symbols:**

```
c000000000718c60-c000000000718d60: audit_file_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void audit_file_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/file.c (ffffffe0003ea36c)
Location: security/apparmor/file.c:43
Inline: False
Direct callers:
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
```
**Symbols:**

```
ffffffe0003ea36c-ffffffe0003ea3e6: audit_file_mask (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void audit_file_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/file.c (0)
Location: security/apparmor/file.c:43
Inline: False
Direct callers:
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
```
**Symbols:**

```
ffffffff814a0da0-ffffffff814a0e43: audit_file_mask (STB_LOCAL)
ffffffff814a216d-ffffffff814a2185: audit_file_mask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void audit_file_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/file.c (0)
Location: security/apparmor/file.c:43
Inline: False
Direct callers:
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
```
**Symbols:**

```
ffffffff814917c0-ffffffff81491863: audit_file_mask (STB_LOCAL)
ffffffff81492b8d-ffffffff81492ba5: audit_file_mask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void audit_file_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/file.c (0)
Location: security/apparmor/file.c:43
Inline: False
Direct callers:
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
```
**Symbols:**

```
ffffffff8149ce40-ffffffff8149cee3: audit_file_mask (STB_LOCAL)
ffffffff8149e20d-ffffffff8149e225: audit_file_mask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void audit_file_mask(struct audit_buffer *ab, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/file.c (0)
Location: security/apparmor/file.c:43
Inline: False
Direct callers:
  - security/apparmor/file.c:file_audit_cb
  - security/apparmor/file.c:file_audit_cb
```
**Symbols:**

```
ffffffff814b53e0-ffffffff814b5483: audit_file_mask (STB_LOCAL)
ffffffff814b67fe-ffffffff814b6816: audit_file_mask.cold (STB_LOCAL)
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
