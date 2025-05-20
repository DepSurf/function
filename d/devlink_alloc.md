# Function: <code>devlink_alloc</code>

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
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct devlink *devlink_alloc(const struct devlink_ops *ops, size_t priv_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:5512
Inline: False
```
**Symbols:**

```
ffffffff819524f6-ffffffff8195250c: devlink_alloc.cold (STB_LOCAL)
ffffffff8194f6f0-ffffffff8194f7e3: devlink_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct devlink *devlink_alloc(const struct devlink_ops *ops, size_t priv_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819860d0)
Location: net/core/devlink.c:6168
Inline: False
```
**Symbols:**

```
ffffffff819860d0-ffffffff819861fd: devlink_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct devlink *devlink_alloc(const struct devlink_ops *ops, size_t priv_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a55f60)
Location: net/core/devlink.c:7098
Inline: False
```
**Symbols:**

```
ffffffff81a55f60-ffffffff81a560c2: devlink_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct devlink *devlink_alloc(const struct devlink_ops *ops, size_t priv_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a5d340)
Location: net/core/devlink.c:7968
Inline: True
```
**Symbols:**

```
ffffffff81a5d340-ffffffff81a5d48c: devlink_alloc.part.0 (STB_LOCAL)
ffffffff81a5d490-ffffffff81a5d504: devlink_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct devlink *devlink_alloc(const struct devlink_ops *ops, size_t priv_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3bbd0)
Location: net/core/devlink.c:8187
Inline: True
```
**Symbols:**

```
ffffffff81a3bbd0-ffffffff81a3bda1: devlink_alloc (STB_GLOBAL)
```
</details>
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
struct devlink *devlink_alloc(const struct devlink_ops *ops, size_t priv_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c254d0)
Location: net/core/devlink.c:6168
Inline: False
```
**Symbols:**

```
ffff800010c254d0-ffff800010c255dc: devlink_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct devlink *devlink_alloc(const struct devlink_ops *ops, size_t priv_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d41178)
Location: net/core/devlink.c:6168
Inline: False
```
**Symbols:**

```
c0d41178-c0d41280: devlink_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct devlink *devlink_alloc(const struct devlink_ops *ops, size_t priv_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d26250)
Location: net/core/devlink.c:6168
Inline: False
```
**Symbols:**

```
c000000000d26250-c000000000d263a4: devlink_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct devlink *devlink_alloc(const struct devlink_ops *ops, size_t priv_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079f658)
Location: net/core/devlink.c:6168
Inline: False
```
**Symbols:**

```
ffffffe00079f658-ffffffe00079f750: devlink_alloc (STB_GLOBAL)
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
struct devlink *devlink_alloc(const struct devlink_ops *ops, size_t priv_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81925f40)
Location: net/core/devlink.c:6168
Inline: False
```
**Symbols:**

```
ffffffff81925f40-ffffffff8192606d: devlink_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct devlink *devlink_alloc(const struct devlink_ops *ops, size_t priv_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818dfcf0)
Location: net/core/devlink.c:6168
Inline: False
```
**Symbols:**

```
ffffffff818dfcf0-ffffffff818dfe1d: devlink_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct devlink *devlink_alloc(const struct devlink_ops *ops, size_t priv_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819770d0)
Location: net/core/devlink.c:6168
Inline: False
```
**Symbols:**

```
ffffffff819770d0-ffffffff819771fd: devlink_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct devlink *devlink_alloc(const struct devlink_ops *ops, size_t priv_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819995c0)
Location: net/core/devlink.c:6168
Inline: False
```
**Symbols:**

```
ffffffff819995c0-ffffffff819996ed: devlink_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
