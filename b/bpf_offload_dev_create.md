# Function: <code>bpf_offload_dev_create</code>

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
struct bpf_offload_dev *bpf_offload_dev_create(const struct bpf_prog_offload_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811defe0)
Location: kernel/bpf/offload.c:637
Inline: False
```
**Symbols:**

```
ffffffff811defe0-ffffffff811df068: bpf_offload_dev_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bpf_offload_dev *bpf_offload_dev_create(const struct bpf_prog_offload_ops *ops, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f4950)
Location: kernel/bpf/offload.c:673
Inline: False
```
**Symbols:**

```
ffffffff811f4950-ffffffff811f49e4: bpf_offload_dev_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bpf_offload_dev *bpf_offload_dev_create(const struct bpf_prog_offload_ops *ops, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81201950)
Location: kernel/bpf/offload.c:673
Inline: False
```
**Symbols:**

```
ffffffff81201950-ffffffff812019f9: bpf_offload_dev_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_offload_dev *bpf_offload_dev_create(const struct bpf_prog_offload_ops *ops, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81228f40)
Location: kernel/bpf/offload.c:673
Inline: False
```
**Symbols:**

```
ffffffff81228f40-ffffffff81228fee: bpf_offload_dev_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_offload_dev *bpf_offload_dev_create(const struct bpf_prog_offload_ops *ops, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81230950)
Location: kernel/bpf/offload.c:673
Inline: False
```
**Symbols:**

```
ffffffff81230950-ffffffff812309fe: bpf_offload_dev_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_offload_dev *bpf_offload_dev_create(const struct bpf_prog_offload_ops *ops, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81234b00)
Location: kernel/bpf/offload.c:673
Inline: False
```
**Symbols:**

```
ffffffff81234b00-ffffffff81234bae: bpf_offload_dev_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct bpf_offload_dev *bpf_offload_dev_create(const struct bpf_prog_offload_ops *ops, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:673
Inline: False
```
**Symbols:**

```
ffffffff81cb9639-ffffffff81cb964d: bpf_offload_dev_create.cold (STB_LOCAL)
ffffffff8126ec00-ffffffff8126ecba: bpf_offload_dev_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct bpf_offload_dev *bpf_offload_dev_create(const struct bpf_prog_offload_ops *ops, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:673
Inline: False
```
**Symbols:**

```
ffffffff81e6aa5d-ffffffff81e6aa71: bpf_offload_dev_create.cold (STB_LOCAL)
ffffffff812bdbf0-ffffffff812bdcb9: bpf_offload_dev_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct bpf_offload_dev *bpf_offload_dev_create(const struct bpf_prog_offload_ops *ops, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:670
Inline: False
```
**Symbols:**

```
ffffffff82061af2-ffffffff82061b06: bpf_offload_dev_create.cold (STB_LOCAL)
ffffffff81321130-ffffffff813211f9: bpf_offload_dev_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_offload_dev *bpf_offload_dev_create(const struct bpf_prog_offload_ops *ops, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81350de0)
Location: kernel/bpf/offload.c:771
Inline: False
```
**Symbols:**

```
ffffffff81350de0-ffffffff81350e38: bpf_offload_dev_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_offload_dev *bpf_offload_dev_create(const struct bpf_prog_offload_ops *ops, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81378210)
Location: kernel/bpf/offload.c:781
Inline: False
```
**Symbols:**

```
ffffffff81378210-ffffffff81378297: bpf_offload_dev_create (STB_GLOBAL)
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
struct bpf_offload_dev *bpf_offload_dev_create(const struct bpf_prog_offload_ops *ops, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffff800010289af8)
Location: kernel/bpf/offload.c:673
Inline: False
```
**Symbols:**

```
ffff800010289af8-ffff800010289bc8: bpf_offload_dev_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bpf_offload_dev *bpf_offload_dev_create(const struct bpf_prog_offload_ops *ops, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c04b9360)
Location: kernel/bpf/offload.c:673
Inline: False
```
**Symbols:**

```
c04b9360-c04b9414: bpf_offload_dev_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bpf_offload_dev *bpf_offload_dev_create(const struct bpf_prog_offload_ops *ops, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c000000000335a50)
Location: kernel/bpf/offload.c:673
Inline: False
```
**Symbols:**

```
c000000000335a50-c000000000335ba4: bpf_offload_dev_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bpf_offload_dev *bpf_offload_dev_create(const struct bpf_prog_offload_ops *ops, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffe0001bdd26)
Location: kernel/bpf/offload.c:673
Inline: False
```
**Symbols:**

```
ffffffe0001bdd26-ffffffe0001bddf6: bpf_offload_dev_create (STB_GLOBAL)
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
struct bpf_offload_dev *bpf_offload_dev_create(const struct bpf_prog_offload_ops *ops, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f9f70)
Location: kernel/bpf/offload.c:673
Inline: False
```
**Symbols:**

```
ffffffff811f9f70-ffffffff811fa019: bpf_offload_dev_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bpf_offload_dev *bpf_offload_dev_create(const struct bpf_prog_offload_ops *ops, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811eccc0)
Location: kernel/bpf/offload.c:673
Inline: False
```
**Symbols:**

```
ffffffff811eccc0-ffffffff811ecd69: bpf_offload_dev_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bpf_offload_dev *bpf_offload_dev_create(const struct bpf_prog_offload_ops *ops, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f7d40)
Location: kernel/bpf/offload.c:673
Inline: False
```
**Symbols:**

```
ffffffff811f7d40-ffffffff811f7de9: bpf_offload_dev_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bpf_offload_dev *bpf_offload_dev_create(const struct bpf_prog_offload_ops *ops, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff812062c0)
Location: kernel/bpf/offload.c:673
Inline: False
```
**Symbols:**

```
ffffffff812062c0-ffffffff81206369: bpf_offload_dev_create (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *priv</code>
</li>
</ul>
</details>
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
