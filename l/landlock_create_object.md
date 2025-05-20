# Function: <code>landlock_create_object</code>

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
struct landlock_object *landlock_create_object(const const struct landlock_object_underops * underops, const void * underobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/object.c (ffffffff81537910)
Location: security/landlock/object.c:20
Inline: False
Direct callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
**Symbols:**

```
ffffffff81537910-ffffffff8153797b: landlock_create_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct landlock_object *landlock_create_object(const const struct landlock_object_underops * underops, const void * underobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/object.c (ffffffff81596110)
Location: security/landlock/object.c:20
Inline: False
Direct callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
**Symbols:**

```
ffffffff81596110-ffffffff8159617b: landlock_create_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct landlock_object *landlock_create_object(const const struct landlock_object_underops * underops, const void * underobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/object.c (ffffffff81638490)
Location: security/landlock/object.c:21
Inline: False
Direct callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
**Symbols:**

```
ffffffff81638490-ffffffff8163850c: landlock_create_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct landlock_object *landlock_create_object(const const struct landlock_object_underops * underops, const void * underobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/object.c (ffffffff816ef8f0)
Location: security/landlock/object.c:21
Inline: False
Direct callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
**Symbols:**

```
ffffffff816ef8f0-ffffffff816ef96c: landlock_create_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct landlock_object *landlock_create_object(const const struct landlock_object_underops * underops, const void * underobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/object.c (ffffffff81729da0)
Location: security/landlock/object.c:21
Inline: False
Direct callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
**Symbols:**

```
ffffffff81729da0-ffffffff81729e1c: landlock_create_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct landlock_object *landlock_create_object(const const struct landlock_object_underops * underops, const void * underobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/object.c (ffffffff8176b110)
Location: security/landlock/object.c:21
Inline: False
Direct callers:
  - security/landlock/fs.c:landlock_append_fs_rule
```
**Symbols:**

```
ffffffff8176b110-ffffffff8176b18c: landlock_create_object (STB_GLOBAL)
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
