# Function: <code>attr_flags_to_mnt_flags</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int attr_flags_to_mnt_flags(u64 attr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134c670)
Location: fs/namespace.c:3494
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
```
**Symbols:**

```
ffffffff8134c670-ffffffff8134c6b5: attr_flags_to_mnt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int attr_flags_to_mnt_flags(u64 attr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139a440)
Location: fs/namespace.c:3569
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
```
**Symbols:**

```
ffffffff8139a440-ffffffff8139a491: attr_flags_to_mnt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int attr_flags_to_mnt_flags(u64 attr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8141cfc0)
Location: fs/namespace.c:3612
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
```
**Symbols:**

```
ffffffff8141cfc0-ffffffff8141d019: attr_flags_to_mnt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int attr_flags_to_mnt_flags(u64 attr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814a92b0)
Location: fs/namespace.c:3718
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
```
**Symbols:**

```
ffffffff814a92b0-ffffffff814a9309: attr_flags_to_mnt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int attr_flags_to_mnt_flags(u64 attr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814de1f0)
Location: fs/namespace.c:3905
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
```
**Symbols:**

```
ffffffff814de1f0-ffffffff814de249: attr_flags_to_mnt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int attr_flags_to_mnt_flags(u64 attr_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81510c40)
Location: fs/namespace.c:3919
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_fsmount
```
**Symbols:**

```
ffffffff81510c40-ffffffff81510c99: attr_flags_to_mnt_flags (STB_LOCAL)
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
