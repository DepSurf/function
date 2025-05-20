# Function: <code>map_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t map_write(struct file *file, const char *buf, size_t count, loff_t *ppos, int cap_setid, struct uid_gid_map *map, struct uid_gid_map *parent_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8111e670)
Location: kernel/user_namespace.c:600
Inline: False
Direct callers:
  - kernel/user_namespace.c:proc_uid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_projid_map_write
```
**Symbols:**

```
ffffffff8111e670-ffffffff8111ece1: map_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t map_write(struct file *file, const char *buf, size_t count, loff_t *ppos, int cap_setid, struct uid_gid_map *map, struct uid_gid_map *parent_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811265c0)
Location: kernel/user_namespace.c:600
Inline: False
Direct callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
```
**Symbols:**

```
ffffffff811265c0-ffffffff81126c3f: map_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t map_write(struct file *file, const char *buf, size_t count, loff_t *ppos, int cap_setid, struct uid_gid_map *map, struct uid_gid_map *parent_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811300b0)
Location: kernel/user_namespace.c:646
Inline: False
Direct callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
```
**Symbols:**

```
ffffffff811300b0-ffffffff8113072c: map_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t map_write(struct file *file, const char *buf, size_t count, loff_t *ppos, int cap_setid, struct uid_gid_map *map, struct uid_gid_map *parent_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff811316c0)
Location: kernel/user_namespace.c:647
Inline: False
Direct callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
```
**Symbols:**

```
ffffffff811316c0-ffffffff81131d93: map_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t map_write(struct file *file, const char *buf, size_t count, loff_t *ppos, int cap_setid, struct uid_gid_map *map, struct uid_gid_map *parent_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff8113e470)
Location: kernel/user_namespace.c:855
Inline: False
Direct callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
```
**Symbols:**

```
ffffffff8113e470-ffffffff8113ebb3: map_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
ssize_t map_write(struct file *file, const char *buf, size_t count, loff_t *ppos, int cap_setid, struct uid_gid_map *map, struct uid_gid_map *parent_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/user_namespace.c (0)
Location: kernel/user_namespace.c:856
Inline: False
Direct callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
```
**Symbols:**

```
ffffffff8114cf40-ffffffff8114d62e: map_write (STB_LOCAL)
ffffffff8114dc9e-ffffffff8114dcaa: map_write.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
ssize_t map_write(struct file *file, const char *buf, size_t count, loff_t *ppos, int cap_setid, struct uid_gid_map *map, struct uid_gid_map *parent_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/user_namespace.c (0)
Location: kernel/user_namespace.c:856
Inline: False
Direct callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
```
**Symbols:**

```
ffffffff81159b60-ffffffff8115a2e9: map_write (STB_LOCAL)
ffffffff8115a96e-ffffffff8115a97a: map_write.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t map_write(struct file *file, const char *buf, size_t count, loff_t *ppos, int cap_setid, struct uid_gid_map *map, struct uid_gid_map *parent_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/user_namespace.c (0)
Location: kernel/user_namespace.c:850
Inline: False
Direct callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
```
**Symbols:**

```
ffffffff811662b0-ffffffff811669c3: map_write (STB_LOCAL)
ffffffff8116701e-ffffffff8116702a: map_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t map_write(struct file *file, const char *buf, size_t count, loff_t *ppos, int cap_setid, struct uid_gid_map *map, struct uid_gid_map *parent_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/user_namespace.c (0)
Location: kernel/user_namespace.c:850
Inline: False
Direct callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
```
**Symbols:**

```
ffffffff81172170-ffffffff81172883: map_write (STB_LOCAL)
ffffffff81172ede-ffffffff81172eea: map_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t map_write(struct file *file, const char *buf, size_t count, loff_t *ppos, int cap_setid, struct uid_gid_map *map, struct uid_gid_map *parent_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/user_namespace.c (0)
Location: kernel/user_namespace.c:850
Inline: False
Direct callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
```
**Symbols:**

```
ffffffff81183e40-ffffffff8118458a: map_write (STB_LOCAL)
ffffffff81184d3e-ffffffff81184d4a: map_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t map_write(struct file *file, const char *buf, size_t count, loff_t *ppos, int cap_setid, struct uid_gid_map *map, struct uid_gid_map *parent_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/user_namespace.c (0)
Location: kernel/user_namespace.c:850
Inline: False
Direct callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
```
**Symbols:**

```
ffffffff81180ba0-ffffffff811812ea: map_write (STB_LOCAL)
ffffffff81be4899-ffffffff81be48a5: map_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t map_write(struct file *file, const char *buf, size_t count, loff_t *ppos, int cap_setid, struct uid_gid_map *map, struct uid_gid_map *parent_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/user_namespace.c (0)
Location: kernel/user_namespace.c:905
Inline: False
Direct callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
```
**Symbols:**

```
ffffffff81181da0-ffffffff81182404: map_write (STB_LOCAL)
ffffffff81bd66f9-ffffffff81bd6705: map_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t map_write(struct file *file, const char *buf, size_t count, loff_t *ppos, int cap_setid, struct uid_gid_map *map, struct uid_gid_map *parent_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/user_namespace.c (0)
Location: kernel/user_namespace.c:921
Inline: False
Direct callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
```
**Symbols:**

```
ffffffff811a9d60-ffffffff811aa3df: map_write (STB_LOCAL)
ffffffff81cb3381-ffffffff81cb338d: map_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t map_write(struct file *file, const char *buf, size_t count, loff_t *ppos, int cap_setid, struct uid_gid_map *map, struct uid_gid_map *parent_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/user_namespace.c (0)
Location: kernel/user_namespace.c:926
Inline: False
Direct callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
```
**Symbols:**

```
ffffffff811db250-ffffffff811db9b5: map_write (STB_LOCAL)
ffffffff81e64173-ffffffff81e6417f: map_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t map_write(struct file *file, const char *buf, size_t count, loff_t *ppos, int cap_setid, struct uid_gid_map *map, struct uid_gid_map *parent_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81220af0)
Location: kernel/user_namespace.c:926
Inline: False
Direct callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
```
**Symbols:**

```
ffffffff81220af0-ffffffff812211a6: map_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t map_write(struct file *file, const char *buf, size_t count, loff_t *ppos, int cap_setid, struct uid_gid_map *map, struct uid_gid_map *parent_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81236f30)
Location: kernel/user_namespace.c:926
Inline: False
Direct callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
```
**Symbols:**

```
ffffffff81236f30-ffffffff81237657: map_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t map_write(struct file *file, const char *buf, size_t count, loff_t *ppos, int cap_setid, struct uid_gid_map *map, struct uid_gid_map *parent_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81250720)
Location: kernel/user_namespace.c:929
Inline: False
Direct callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
```
**Symbols:**

```
ffffffff81250720-ffffffff81250e47: map_write (STB_LOCAL)
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
ssize_t map_write(struct file *file, const char *buf, size_t count, loff_t *ppos, int cap_setid, struct uid_gid_map *map, struct uid_gid_map *parent_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffff8000101e5e48)
Location: kernel/user_namespace.c:850
Inline: False
Direct callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
```
**Symbols:**

```
ffff8000101e5e48-ffff8000101e644c: map_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t map_write(struct file *file, const char *buf, size_t count, loff_t *ppos, int cap_setid, struct uid_gid_map *map, struct uid_gid_map *parent_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (c042687c)
Location: kernel/user_namespace.c:850
Inline: False
Direct callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
```
**Symbols:**

```
c042687c-c0426ee0: map_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t map_write(struct file *file, const char *buf, size_t count, loff_t *ppos, int cap_setid, struct uid_gid_map *map, struct uid_gid_map *parent_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (c000000000256750)
Location: kernel/user_namespace.c:850
Inline: False
Direct callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
```
**Symbols:**

```
c000000000256750-c000000000256ef8: map_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t map_write(struct file *file, const char *buf, size_t count, loff_t *ppos, int cap_setid, struct uid_gid_map *map, struct uid_gid_map *parent_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffe00015bb20)
Location: kernel/user_namespace.c:850
Inline: False
Direct callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
```
**Symbols:**

```
ffffffe00015bb20-ffffffe00015c092: map_write (STB_LOCAL)
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
ssize_t map_write(struct file *file, const char *buf, size_t count, loff_t *ppos, int cap_setid, struct uid_gid_map *map, struct uid_gid_map *parent_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/user_namespace.c (0)
Location: kernel/user_namespace.c:850
Inline: False
Direct callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
```
**Symbols:**

```
ffffffff8116a790-ffffffff8116aea3: map_write (STB_LOCAL)
ffffffff8116b4fe-ffffffff8116b50a: map_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t map_write(struct file *file, const char *buf, size_t count, loff_t *ppos, int cap_setid, struct uid_gid_map *map, struct uid_gid_map *parent_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/user_namespace.c (0)
Location: kernel/user_namespace.c:850
Inline: False
Direct callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
```
**Symbols:**

```
ffffffff8115d990-ffffffff8115e0a3: map_write (STB_LOCAL)
ffffffff8115e6fe-ffffffff8115e70a: map_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t map_write(struct file *file, const char *buf, size_t count, loff_t *ppos, int cap_setid, struct uid_gid_map *map, struct uid_gid_map *parent_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/user_namespace.c (0)
Location: kernel/user_namespace.c:850
Inline: False
Direct callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
```
**Symbols:**

```
ffffffff81168560-ffffffff81168c73: map_write (STB_LOCAL)
ffffffff811692ce-ffffffff811692da: map_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t map_write(struct file *file, const char *buf, size_t count, loff_t *ppos, int cap_setid, struct uid_gid_map *map, struct uid_gid_map *parent_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/user_namespace.c (0)
Location: kernel/user_namespace.c:850
Inline: False
Direct callers:
  - kernel/user_namespace.c:proc_projid_map_write
  - kernel/user_namespace.c:proc_gid_map_write
  - kernel/user_namespace.c:proc_uid_map_write
```
**Symbols:**

```
ffffffff81175c50-ffffffff81176363: map_write (STB_LOCAL)
ffffffff811769be-ffffffff811769ca: map_write.cold (STB_LOCAL)
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
