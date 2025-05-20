# Function: <code>expand_fdtable</code>

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
In fs/file.c (ffffffff8122a078)
Location: fs/file.c:165
Inline: True
Inline callers:
  - fs/file.c:expand_files
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
In fs/file.c (ffffffff812527c8)
Location: fs/file.c:166
Inline: True
Inline callers:
  - fs/file.c:expand_files
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
In fs/file.c (ffffffff81265a3c)
Location: fs/file.c:166
Inline: True
Inline callers:
  - fs/file.c:expand_files
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
In fs/file.c (ffffffff81273178)
Location: fs/file.c:152
Inline: True
Inline callers:
  - fs/file.c:expand_files
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
In fs/file.c (ffffffff81295aa8)
Location: fs/file.c:153
Inline: True
Inline callers:
  - fs/file.c:expand_files
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
In fs/file.c (ffffffff812bbdc8)
Location: fs/file.c:148
Inline: True
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
In fs/file.c (ffffffff812d0fb8)
Location: fs/file.c:148
Inline: True
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
In fs/file.c (ffffffff812edfe9)
Location: fs/file.c:148
Inline: True
Inline callers:
  - fs/file.c:expand_files
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
In fs/file.c (ffffffff812ffaa9)
Location: fs/file.c:148
Inline: True
Inline callers:
  - fs/file.c:expand_files
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int expand_fdtable(struct files_struct *files, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81338b60)
Location: fs/file.c:148
Inline: False
Direct callers:
  - fs/file.c:expand_files
```
**Symbols:**

```
ffffffff81338b60-ffffffff81338c7f: expand_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int expand_fdtable(struct files_struct *files, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff813445e0)
Location: fs/file.c:153
Inline: False
Direct callers:
  - fs/file.c:expand_files
```
**Symbols:**

```
ffffffff813445e0-ffffffff813446ff: expand_fdtable (STB_LOCAL)
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
In fs/file.c (ffffffff8134aa77)
Location: fs/file.c:153
Inline: True
Inline callers:
  - fs/file.c:expand_files
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
In fs/file.c (ffffffff81398836)
Location: fs/file.c:153
Inline: True
Inline callers:
  - fs/file.c:expand_files
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
In fs/file.c (ffffffff8141b086)
Location: fs/file.c:169
Inline: True
Inline callers:
  - fs/file.c:expand_files
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
In fs/file.c (ffffffff814a7116)
Location: fs/file.c:169
Inline: True
Inline callers:
  - fs/file.c:expand_files
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
In fs/file.c (ffffffff814dc0ef)
Location: fs/file.c:169
Inline: True
Inline callers:
  - fs/file.c:expand_files
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
In fs/file.c (ffffffff8150e40f)
Location: fs/file.c:169
Inline: True
Inline callers:
  - fs/file.c:expand_files
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
In fs/file.c (ffff8000103b158c)
Location: fs/file.c:148
Inline: True
Inline callers:
  - fs/file.c:expand_files
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
In fs/file.c (c0590628)
Location: fs/file.c:148
Inline: True
Inline callers:
  - fs/file.c:expand_files
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
In fs/file.c (c0000000004ac848)
Location: fs/file.c:148
Inline: True
Inline callers:
  - fs/file.c:expand_files
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
In fs/file.c (ffffffe00027567c)
Location: fs/file.c:148
Inline: True
Inline callers:
  - fs/file.c:expand_files
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
In fs/file.c (ffffffff812f8089)
Location: fs/file.c:148
Inline: True
Inline callers:
  - fs/file.c:expand_files
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
In fs/file.c (ffffffff812e8ca9)
Location: fs/file.c:148
Inline: True
Inline callers:
  - fs/file.c:expand_files
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
In fs/file.c (ffffffff812f5e99)
Location: fs/file.c:148
Inline: True
Inline callers:
  - fs/file.c:expand_files
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
In fs/file.c (ffffffff81306fb9)
Location: fs/file.c:148
Inline: True
Inline callers:
  - fs/file.c:expand_files
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
</ul>
