# Function: <code>audit_mnt_flags</code>

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
In security/apparmor/mount.c (ffffffff8138e7a6)
Location: security/apparmor/mount.c:30
Inline: True
Inline callers:
  - security/apparmor/mount.c:audit_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813c9736)
Location: security/apparmor/mount.c:30
Inline: True
Inline callers:
  - security/apparmor/mount.c:audit_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813e0da6)
Location: security/apparmor/mount.c:30
Inline: True
Inline callers:
  - security/apparmor/mount.c:audit_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813efa7e)
Location: security/apparmor/mount.c:30
Inline: True
Inline callers:
  - security/apparmor/mount.c:audit_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814179ce)
Location: security/apparmor/mount.c:30
Inline: True
Inline callers:
  - security/apparmor/mount.c:audit_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81449e4e)
Location: security/apparmor/mount.c:30
Inline: True
Inline callers:
  - security/apparmor/mount.c:audit_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81466dae)
Location: security/apparmor/mount.c:31
Inline: True
Inline callers:
  - security/apparmor/mount.c:audit_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81493e7e)
Location: security/apparmor/mount.c:27
Inline: True
Inline callers:
  - security/apparmor/mount.c:audit_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814addae)
Location: security/apparmor/mount.c:27
Inline: True
Inline callers:
  - security/apparmor/mount.c:audit_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void audit_mnt_flags(struct audit_buffer *ab, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8150cce0)
Location: security/apparmor/mount.c:27
Inline: False
Direct callers:
  - security/apparmor/mount.c:audit_cb
```
**Symbols:**

```
ffffffff8150cce0-ffffffff8150cfd7: audit_mnt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void audit_mnt_flags(struct audit_buffer *ab, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81529b70)
Location: security/apparmor/mount.c:27
Inline: False
Direct callers:
  - security/apparmor/mount.c:audit_cb
```
**Symbols:**

```
ffffffff81529b70-ffffffff81529e67: audit_mnt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void audit_mnt_flags(struct audit_buffer *ab, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8152ff60)
Location: security/apparmor/mount.c:27
Inline: False
Direct callers:
  - security/apparmor/mount.c:audit_cb
```
**Symbols:**

```
ffffffff8152ff60-ffffffff81530257: audit_mnt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void audit_mnt_flags(struct audit_buffer *ab, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8158e380)
Location: security/apparmor/mount.c:27
Inline: False
Direct callers:
  - security/apparmor/mount.c:audit_cb
```
**Symbols:**

```
ffffffff8158e380-ffffffff8158e677: audit_mnt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void audit_mnt_flags(struct audit_buffer *ab, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8162f420)
Location: security/apparmor/mount.c:27
Inline: False
Direct callers:
  - security/apparmor/mount.c:audit_cb
```
**Symbols:**

```
ffffffff8162f420-ffffffff8162f72b: audit_mnt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void audit_mnt_flags(struct audit_buffer *ab, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff816e4050)
Location: security/apparmor/mount.c:27
Inline: False
Direct callers:
  - security/apparmor/mount.c:audit_cb
```
**Symbols:**

```
ffffffff816e4050-ffffffff816e435b: audit_mnt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void audit_mnt_flags(struct audit_buffer *ab, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8171d5c0)
Location: security/apparmor/mount.c:27
Inline: False
Direct callers:
  - security/apparmor/mount.c:audit_cb
```
**Symbols:**

```
ffffffff8171d5c0-ffffffff8171d9a3: audit_mnt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void audit_mnt_flags(struct audit_buffer *ab, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8175c010)
Location: security/apparmor/mount.c:27
Inline: False
Direct callers:
  - security/apparmor/mount.c:audit_cb
```
**Symbols:**

```
ffffffff8175c010-ffffffff8175c3f3: audit_mnt_flags (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffff8000105a54f0)
Location: security/apparmor/mount.c:27
Inline: True
Inline callers:
  - security/apparmor/mount.c:audit_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (c07555bc)
Location: security/apparmor/mount.c:27
Inline: True
Inline callers:
  - security/apparmor/mount.c:audit_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (c000000000721320)
Location: security/apparmor/mount.c:27
Inline: True
Inline callers:
  - security/apparmor/mount.c:audit_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffe0003ef0a6)
Location: security/apparmor/mount.c:27
Inline: True
Inline callers:
  - security/apparmor/mount.c:audit_cb
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814a638e)
Location: security/apparmor/mount.c:27
Inline: True
Inline callers:
  - security/apparmor/mount.c:audit_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81496dae)
Location: security/apparmor/mount.c:27
Inline: True
Inline callers:
  - security/apparmor/mount.c:audit_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814a242e)
Location: security/apparmor/mount.c:27
Inline: True
Inline callers:
  - security/apparmor/mount.c:audit_cb
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814babee)
Location: security/apparmor/mount.c:27
Inline: True
Inline callers:
  - security/apparmor/mount.c:audit_cb
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
