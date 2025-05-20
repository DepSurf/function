# Function: <code>eventfd_ctx_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct eventfd_ctx *eventfd_ctx_get(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81259167)
Location: fs/eventfd.c:88
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
**Symbols:**

```
ffffffff812592d0-ffffffff8125931d: eventfd_ctx_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct eventfd_ctx *eventfd_ctx_get(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81281b47)
Location: fs/eventfd.c:88
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
**Symbols:**

```
ffffffff81281ca0-ffffffff81281cee: eventfd_ctx_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct eventfd_ctx *eventfd_ctx_get(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff81295677)
Location: fs/eventfd.c:88
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
**Symbols:**

```
ffffffff812957d0-ffffffff8129581e: eventfd_ctx_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct eventfd_ctx *eventfd_ctx_get(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff812a297c)
Location: fs/eventfd.c:88
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
**Symbols:**

```
ffffffff812a26d0-ffffffff812a26e1: eventfd_ctx_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct eventfd_ctx *eventfd_ctx_get(struct eventfd_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventfd.c (ffffffff812c5c2c)
Location: fs/eventfd.c:88
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_fdget
```
**Symbols:**

```
ffffffff812c5d60-ffffffff812c5d77: eventfd_ctx_get (STB_GLOBAL)
```
</details>
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
</ul>
