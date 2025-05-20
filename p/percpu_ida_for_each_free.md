# Function: <code>percpu_ida_for_each_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int percpu_ida_for_each_free(struct percpu_ida *pool, percpu_ida_cb fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_ida.c (ffffffff813ff630)
Location: lib/percpu_ida.c:341
Inline: False
```
**Symbols:**

```
ffffffff813ff630-ffffffff813ff73f: percpu_ida_for_each_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int percpu_ida_for_each_free(struct percpu_ida *pool, percpu_ida_cb fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_ida.c (ffffffff81446d10)
Location: lib/percpu_ida.c:341
Inline: False
```
**Symbols:**

```
ffffffff81446d10-ffffffff81446e2e: percpu_ida_for_each_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int percpu_ida_for_each_free(struct percpu_ida *pool, percpu_ida_cb fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_ida.c (ffffffff81465500)
Location: lib/percpu_ida.c:341
Inline: False
```
**Symbols:**

```
ffffffff81465500-ffffffff8146562c: percpu_ida_for_each_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int percpu_ida_for_each_free(struct percpu_ida *pool, percpu_ida_cb fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_ida.c (ffffffff8146a8b0)
Location: lib/percpu_ida.c:342
Inline: False
```
**Symbols:**

```
ffffffff8146a8b0-ffffffff8146a9ce: percpu_ida_for_each_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int percpu_ida_for_each_free(struct percpu_ida *pool, percpu_ida_cb fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_ida.c (ffffffff81496b80)
Location: lib/percpu_ida.c:342
Inline: False
```
**Symbols:**

```
ffffffff81496b80-ffffffff81496cb0: percpu_ida_for_each_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int percpu_ida_for_each_free(struct percpu_ida *pool, percpu_ida_cb fn, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_ida.c (ffffffff814cb900)
Location: lib/percpu_ida.c:323
Inline: False
```
**Symbols:**

```
ffffffff814cb900-ffffffff814cba33: percpu_ida_for_each_free (STB_GLOBAL)
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
