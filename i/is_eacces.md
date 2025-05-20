# Function: <code>is_eacces</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff81639e9e)
Location: security/landlock/fs.c:408
Inline: True
Inline callers:
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
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
In security/landlock/fs.c (ffffffff816f2b84)
Location: security/landlock/fs.c:428
Inline: True
Inline callers:
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
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
In security/landlock/fs.c (ffffffff8172d059)
Location: security/landlock/fs.c:428
Inline: True
Inline callers:
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool is_eacces(const const layer_mask_t[15] * layer_masks, const access_mask_t access_request);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff8176d940)
Location: security/landlock/fs.c:339
Inline: False
Direct callers:
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
```
**Symbols:**

```
ffffffff8176d940-ffffffff8176d9fb: is_eacces (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
