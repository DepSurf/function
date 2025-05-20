# Function: <code>rfkill_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rfkill *rfkill_alloc(const char *name, struct device *parent, const enum rfkill_type type, const struct rfkill_ops *ops, void *ops_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff818116d0)
Location: net/rfkill/core.c:858
Inline: False
```
**Symbols:**

```
ffffffff818116d0-ffffffff81811807: rfkill_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rfkill *rfkill_alloc(const char *name, struct device *parent, const enum rfkill_type type, const struct rfkill_ops *ops, void *ops_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81884540)
Location: net/rfkill/core.c:857
Inline: False
```
**Symbols:**

```
ffffffff81884540-ffffffff81884677: rfkill_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rfkill *rfkill_alloc(const char *name, struct device *parent, const enum rfkill_type type, const struct rfkill_ops *ops, void *ops_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff818b8db0)
Location: net/rfkill/core.c:857
Inline: False
```
**Symbols:**

```
ffffffff818b8db0-ffffffff818b8ee7: rfkill_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rfkill *rfkill_alloc(const char *name, struct device *parent, const enum rfkill_type type, const struct rfkill_ops *ops, void *ops_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff818df7a0)
Location: net/rfkill/core.c:915
Inline: False
```
**Symbols:**

```
ffffffff818df7a0-ffffffff818df889: rfkill_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rfkill *rfkill_alloc(const char *name, struct device *parent, const enum rfkill_type type, const struct rfkill_ops *ops, void *ops_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff819654b0)
Location: net/rfkill/core.c:915
Inline: False
```
**Symbols:**

```
ffffffff819654b0-ffffffff81965599: rfkill_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rfkill *rfkill_alloc(const char *name, struct device *parent, const enum rfkill_type type, const struct rfkill_ops *ops, void *ops_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff819bed30)
Location: net/rfkill/core.c:929
Inline: False
```
**Symbols:**

```
ffffffff819bed30-ffffffff819bee19: rfkill_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rfkill *rfkill_alloc(const char *name, struct device *parent, const enum rfkill_type type, const struct rfkill_ops *ops, void *ops_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff819f60c0)
Location: net/rfkill/core.c:931
Inline: False
```
**Symbols:**

```
ffffffff819f60c0-ffffffff819f61a9: rfkill_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct rfkill *rfkill_alloc(const char *name, struct device *parent, const enum rfkill_type type, const struct rfkill_ops *ops, void *ops_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/rfkill/core.c (0)
Location: net/rfkill/core.c:919
Inline: False
```
**Symbols:**

```
ffffffff81a66356-ffffffff81a663ae: rfkill_alloc.cold (STB_LOCAL)
ffffffff81a65ae0-ffffffff81a65bd0: rfkill_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rfkill *rfkill_alloc(const char *name, struct device *parent, const enum rfkill_type type, const struct rfkill_ops *ops, void *ops_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81a9c640)
Location: net/rfkill/core.c:919
Inline: False
```
**Symbols:**

```
ffffffff81a9c640-ffffffff81a9c737: rfkill_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rfkill *rfkill_alloc(const char *name, struct device *parent, const enum rfkill_type type, const struct rfkill_ops *ops, void *ops_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81b97470)
Location: net/rfkill/core.c:919
Inline: False
```
**Symbols:**

```
ffffffff81b97470-ffffffff81b97567: rfkill_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rfkill *rfkill_alloc(const char *name, struct device *parent, const enum rfkill_type type, const struct rfkill_ops *ops, void *ops_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81ba7140)
Location: net/rfkill/core.c:949
Inline: False
```
**Symbols:**

```
ffffffff81ba7140-ffffffff81ba723a: rfkill_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rfkill *rfkill_alloc(const char *name, struct device *parent, const enum rfkill_type type, const struct rfkill_ops *ops, void *ops_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81b962d0)
Location: net/rfkill/core.c:950
Inline: False
```
**Symbols:**

```
ffffffff81b962d0-ffffffff81b963ca: rfkill_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rfkill *rfkill_alloc(const char *name, struct device *parent, const enum rfkill_type type, const struct rfkill_ops *ops, void *ops_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81c62be0)
Location: net/rfkill/core.c:950
Inline: False
```
**Symbols:**

```
ffffffff81c62be0-ffffffff81c62cda: rfkill_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rfkill *rfkill_alloc(const char *name, struct device *parent, const enum rfkill_type type, const struct rfkill_ops *ops, void *ops_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81e05510)
Location: net/rfkill/core.c:962
Inline: False
```
**Symbols:**

```
ffffffff81e05510-ffffffff81e0560b: rfkill_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rfkill *rfkill_alloc(const char *name, struct device *parent, const enum rfkill_type type, const struct rfkill_ops *ops, void *ops_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81fda790)
Location: net/rfkill/core.c:962
Inline: False
```
**Symbols:**

```
ffffffff81fda790-ffffffff81fda88b: rfkill_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rfkill *rfkill_alloc(const char *name, struct device *parent, const enum rfkill_type type, const struct rfkill_ops *ops, void *ops_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff82056450)
Location: net/rfkill/core.c:962
Inline: False
```
**Symbols:**

```
ffffffff82056450-ffffffff82056579: rfkill_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rfkill *rfkill_alloc(const char *name, struct device *parent, const enum rfkill_type type, const struct rfkill_ops *ops, void *ops_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff82128ce0)
Location: net/rfkill/core.c:984
Inline: False
```
**Symbols:**

```
ffffffff82128ce0-ffffffff82128e09: rfkill_alloc (STB_GLOBAL)
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
struct rfkill *rfkill_alloc(const char *name, struct device *parent, const enum rfkill_type type, const struct rfkill_ops *ops, void *ops_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffff800010d6b970)
Location: net/rfkill/core.c:919
Inline: False
```
**Symbols:**

```
ffff800010d6b970-ffff800010d6ba74: rfkill_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rfkill *rfkill_alloc(const char *name, struct device *parent, const enum rfkill_type type, const struct rfkill_ops *ops, void *ops_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (c0e6aa70)
Location: net/rfkill/core.c:919
Inline: False
```
**Symbols:**

```
c0e6aa70-c0e6aba0: rfkill_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rfkill *rfkill_alloc(const char *name, struct device *parent, const enum rfkill_type type, const struct rfkill_ops *ops, void *ops_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (c000000000ea9dc0)
Location: net/rfkill/core.c:919
Inline: False
```
**Symbols:**

```
c000000000ea9dc0-c000000000ea9f2c: rfkill_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rfkill *rfkill_alloc(const char *name, struct device *parent, const enum rfkill_type type, const struct rfkill_ops *ops, void *ops_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffe00089edda)
Location: net/rfkill/core.c:919
Inline: False
```
**Symbols:**

```
ffffffe00089edda-ffffffe00089eeae: rfkill_alloc (STB_GLOBAL)
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
struct rfkill *rfkill_alloc(const char *name, struct device *parent, const enum rfkill_type type, const struct rfkill_ops *ops, void *ops_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81a3b9d0)
Location: net/rfkill/core.c:919
Inline: False
```
**Symbols:**

```
ffffffff81a3b9d0-ffffffff81a3bac7: rfkill_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rfkill *rfkill_alloc(const char *name, struct device *parent, const enum rfkill_type type, const struct rfkill_ops *ops, void *ops_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff819f85f0)
Location: net/rfkill/core.c:919
Inline: False
```
**Symbols:**

```
ffffffff819f85f0-ffffffff819f86e7: rfkill_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rfkill *rfkill_alloc(const char *name, struct device *parent, const enum rfkill_type type, const struct rfkill_ops *ops, void *ops_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81aa7880)
Location: net/rfkill/core.c:919
Inline: False
```
**Symbols:**

```
ffffffff81aa7880-ffffffff81aa7977: rfkill_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rfkill *rfkill_alloc(const char *name, struct device *parent, const enum rfkill_type type, const struct rfkill_ops *ops, void *ops_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81ab3c20)
Location: net/rfkill/core.c:919
Inline: False
```
**Symbols:**

```
ffffffff81ab3c20-ffffffff81ab3d17: rfkill_alloc (STB_GLOBAL)
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
