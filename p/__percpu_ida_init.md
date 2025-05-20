# Function: <code>__percpu_ida_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __percpu_ida_init(struct percpu_ida *pool, long unsigned int nr_tags, long unsigned int max_size, long unsigned int batch_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_ida.c (ffffffff813ff4c0)
Location: lib/percpu_ida.c:286
Inline: False
```
**Symbols:**

```
ffffffff813ff4c0-ffffffff813ff626: __percpu_ida_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __percpu_ida_init(struct percpu_ida *pool, long unsigned int nr_tags, long unsigned int max_size, long unsigned int batch_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_ida.c (ffffffff81446ba0)
Location: lib/percpu_ida.c:286
Inline: False
```
**Symbols:**

```
ffffffff81446ba0-ffffffff81446d06: __percpu_ida_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __percpu_ida_init(struct percpu_ida *pool, long unsigned int nr_tags, long unsigned int max_size, long unsigned int batch_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_ida.c (ffffffff81465380)
Location: lib/percpu_ida.c:286
Inline: False
```
**Symbols:**

```
ffffffff81465380-ffffffff814654fd: __percpu_ida_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __percpu_ida_init(struct percpu_ida *pool, long unsigned int nr_tags, long unsigned int max_size, long unsigned int batch_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_ida.c (ffffffff8146a3e0)
Location: lib/percpu_ida.c:287
Inline: False
```
**Symbols:**

```
ffffffff8146a3e0-ffffffff8146a558: __percpu_ida_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __percpu_ida_init(struct percpu_ida *pool, long unsigned int nr_tags, long unsigned int max_size, long unsigned int batch_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_ida.c (ffffffff814966e0)
Location: lib/percpu_ida.c:287
Inline: False
```
**Symbols:**

```
ffffffff814966e0-ffffffff8149683e: __percpu_ida_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __percpu_ida_init(struct percpu_ida *pool, long unsigned int nr_tags, long unsigned int max_size, long unsigned int batch_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/percpu_ida.c (0)
Location: lib/percpu_ida.c:268
Inline: False
```
**Symbols:**

```
ffffffff814cc01b-ffffffff814cc031: __percpu_ida_init.cold.1 (STB_LOCAL)
ffffffff814cba80-ffffffff814cbbcc: __percpu_ida_init (STB_GLOBAL)
```
</details>
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
</ul>
