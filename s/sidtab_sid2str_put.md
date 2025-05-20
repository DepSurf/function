# Function: <code>sidtab_sid2str_put</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sidtab_sid2str_put(struct sidtab *s, struct sidtab_entry *entry, const char *str, u32 str_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff814c0dc6)
Location: security/selinux/ss/sidtab.c:522
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_sid2str_get
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_sid2str_get
```
**Symbols:**

```
ffffffff814bfc10-ffffffff814bfd8e: sidtab_sid2str_put.part.0 (STB_LOCAL)
ffffffff814c0d50-ffffffff814c0d68: sidtab_sid2str_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sidtab_sid2str_put(struct sidtab *s, struct sidtab_entry *entry, const char *str, u32 str_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff814de88f)
Location: security/selinux/ss/sidtab.c:532
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_sid2str_get
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_sid2str_get
```
**Symbols:**

```
ffffffff814dd670-ffffffff814dd7ee: sidtab_sid2str_put.part.0 (STB_LOCAL)
ffffffff814de810-ffffffff814de828: sidtab_sid2str_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sidtab_sid2str_put(struct sidtab *s, struct sidtab_entry *entry, const char *str, u32 str_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff814e525f)
Location: security/selinux/ss/sidtab.c:553
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_sid2str_get
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_sid2str_get
```
**Symbols:**

```
ffffffff814e3fe0-ffffffff814e415b: sidtab_sid2str_put.part.0 (STB_LOCAL)
ffffffff814e51e0-ffffffff814e51f8: sidtab_sid2str_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sidtab_sid2str_put(struct sidtab *s, struct sidtab_entry *entry, const char *str, u32 str_len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8153e94f)
Location: security/selinux/ss/sidtab.c:553
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_sid2str_get
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_sid2str_get
```
**Symbols:**

```
ffffffff8153d400-ffffffff8153d57b: sidtab_sid2str_put.part.0 (STB_LOCAL)
ffffffff8153e8d0-ffffffff8153e8e8: sidtab_sid2str_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sidtab_sid2str_put(struct sidtab *s, struct sidtab_entry *entry, const char *str, u32 str_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff815d62d0)
Location: security/selinux/ss/sidtab.c:553
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_sid2str_get
```
**Symbols:**

```
ffffffff815d62d0-ffffffff815d6482: sidtab_sid2str_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sidtab_sid2str_put(struct sidtab *s, struct sidtab_entry *entry, const char *str, u32 str_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff816845b0)
Location: security/selinux/ss/sidtab.c:558
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_sid2str_get
```
**Symbols:**

```
ffffffff816845b0-ffffffff81684762: sidtab_sid2str_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sidtab_sid2str_put(struct sidtab *s, struct sidtab_entry *entry, const char *str, u32 str_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff816bc920)
Location: security/selinux/ss/sidtab.c:558
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_sid2str_get
```
**Symbols:**

```
ffffffff816bc920-ffffffff816bcad3: sidtab_sid2str_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sidtab_sid2str_put(struct sidtab *s, struct sidtab_entry *entry, const char *str, u32 str_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff816f9450)
Location: security/selinux/ss/sidtab.c:558
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_sid2str_get
```
**Symbols:**

```
ffffffff816f9450-ffffffff816f9603: sidtab_sid2str_put (STB_GLOBAL)
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
