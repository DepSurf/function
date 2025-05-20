# Function: <code>sidtab_find_context</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sidtab_find_context(union sidtab_entry_inner entry, u32 *pos, u32 count, u32 level, struct context *context, u32 *index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff81423d40)
Location: security/selinux/ss/sidtab.c:175
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_find_context
```
**Symbols:**

```
ffffffff81423d40-ffffffff81423eae: sidtab_find_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sidtab_find_context(union sidtab_entry_inner entry, u32 *pos, u32 count, u32 level, struct context *context, u32 *index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff814518a0)
Location: security/selinux/ss/sidtab.c:175
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_find_context
```
**Symbols:**

```
ffffffff814518a0-ffffffff81451a26: sidtab_find_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sidtab_find_context(union sidtab_entry_inner entry, u32 *pos, u32 count, u32 level, struct context *context, u32 *index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8146b680)
Location: security/selinux/ss/sidtab.c:173
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_find_context
```
**Symbols:**

```
ffffffff8146b680-ffffffff8146b806: sidtab_find_context (STB_LOCAL)
```
</details>
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
int sidtab_find_context(union sidtab_entry_inner entry, u32 *pos, u32 count, u32 level, struct context *context, u32 *index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffff80001055a8c0)
Location: security/selinux/ss/sidtab.c:173
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_find_context
```
**Symbols:**

```
ffff80001055a8c0-ffff80001055aa60: sidtab_find_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sidtab_find_context(union sidtab_entry_inner entry, u32 *pos, u32 count, u32 level, struct context *context, u32 *index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (c070f0e8)
Location: security/selinux/ss/sidtab.c:173
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_find_context
```
**Symbols:**

```
c070f0e8-c070f28c: sidtab_find_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sidtab_find_context(union sidtab_entry_inner entry, u32 *pos, u32 count, u32 level, struct context *context, u32 *index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (c0000000006b8ca0)
Location: security/selinux/ss/sidtab.c:173
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_find_context
```
**Symbols:**

```
c0000000006b8ca0-c0000000006b90e4: sidtab_find_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sidtab_find_context(union sidtab_entry_inner entry, u32 *pos, u32 count, u32 level, struct context *context, u32 *index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffe0003b14e8)
Location: security/selinux/ss/sidtab.c:173
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_find_context
```
**Symbols:**

```
ffffffe0003b14e8-ffffffe0003b163a: sidtab_find_context (STB_LOCAL)
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
int sidtab_find_context(union sidtab_entry_inner entry, u32 *pos, u32 count, u32 level, struct context *context, u32 *index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff81463c60)
Location: security/selinux/ss/sidtab.c:173
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_find_context
```
**Symbols:**

```
ffffffff81463c60-ffffffff81463de6: sidtab_find_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sidtab_find_context(union sidtab_entry_inner entry, u32 *pos, u32 count, u32 level, struct context *context, u32 *index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff81454690)
Location: security/selinux/ss/sidtab.c:173
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_find_context
```
**Symbols:**

```
ffffffff81454690-ffffffff81454816: sidtab_find_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sidtab_find_context(union sidtab_entry_inner entry, u32 *pos, u32 count, u32 level, struct context *context, u32 *index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8145fd00)
Location: security/selinux/ss/sidtab.c:173
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_find_context
```
**Symbols:**

```
ffffffff8145fd00-ffffffff8145fe86: sidtab_find_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sidtab_find_context(union sidtab_entry_inner entry, u32 *pos, u32 count, u32 level, struct context *context, u32 *index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff81477510)
Location: security/selinux/ss/sidtab.c:173
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_context_to_sid
  - security/selinux/ss/sidtab.c:sidtab_find_context
```
**Symbols:**

```
ffffffff81477510-ffffffff81477696: sidtab_find_context (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
