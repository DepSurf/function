# Function: <code>cec_allocate_adapter</code>

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
struct cec_adapter *cec_allocate_adapter(const struct cec_adap_ops *ops, void *priv, const char *name, u32 caps, u8 available_las);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (ffffffff818037b0)
Location: drivers/media/cec/cec-core.c:251
Inline: False
```
**Symbols:**

```
ffffffff818037b0-ffffffff81803a1d: cec_allocate_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct cec_adapter *cec_allocate_adapter(const struct cec_adap_ops *ops, void *priv, const char *name, u32 caps, u8 available_las);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-core.c (0)
Location: drivers/media/cec/cec-core.c:253
Inline: False
```
**Symbols:**

```
ffffffff81844f03-ffffffff81844f7e: cec_allocate_adapter.cold (STB_LOCAL)
ffffffff818449d0-ffffffff81844bea: cec_allocate_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct cec_adapter *cec_allocate_adapter(const struct cec_adap_ops *ops, void *priv, const char *name, u32 caps, u8 available_las);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-core.c (0)
Location: drivers/media/cec/cec-core.c:253
Inline: False
```
**Symbols:**

```
ffffffff81876850-ffffffff8187687d: cec_allocate_adapter.cold (STB_LOCAL)
ffffffff81876300-ffffffff81876531: cec_allocate_adapter (STB_GLOBAL)
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
struct cec_adapter *cec_allocate_adapter(const struct cec_adap_ops *ops, void *priv, const char *name, u32 caps, u8 available_las);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (ffff800010abd8c0)
Location: drivers/media/cec/cec-core.c:253
Inline: False
Direct callers:
  - drivers/media/cec/cec-pin.c:cec_pin_allocate_adapter
```
**Symbols:**

```
ffff800010abd8c0-ffff800010abdad4: cec_allocate_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct cec_adapter *cec_allocate_adapter(const struct cec_adap_ops *ops, void *priv, const char *name, u32 caps, u8 available_las);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (c0b9f744)
Location: drivers/media/cec/cec-core.c:253
Inline: False
```
**Symbols:**

```
c0b9f744-c0b9f960: cec_allocate_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct cec_adapter *cec_allocate_adapter(const struct cec_adap_ops *ops, void *priv, const char *name, u32 caps, u8 available_las);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (c000000000b9f460)
Location: drivers/media/cec/cec-core.c:253
Inline: False
```
**Symbols:**

```
c000000000b9f460-c000000000b9f6ec: cec_allocate_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct cec_adapter *cec_allocate_adapter(const struct cec_adap_ops *ops, void *priv, const char *name, u32 caps, u8 available_las);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-core.c (ffffffe0006bfbc0)
Location: drivers/media/cec/cec-core.c:253
Inline: False
```
**Symbols:**

```
ffffffe0006bfbc0-ffffffe0006bfd94: cec_allocate_adapter (STB_GLOBAL)
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
struct cec_adapter *cec_allocate_adapter(const struct cec_adap_ops *ops, void *priv, const char *name, u32 caps, u8 available_las);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-core.c (0)
Location: drivers/media/cec/cec-core.c:253
Inline: False
```
**Symbols:**

```
ffffffff8181edc0-ffffffff8181eded: cec_allocate_adapter.cold (STB_LOCAL)
ffffffff8181e870-ffffffff8181eaa1: cec_allocate_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct cec_adapter *cec_allocate_adapter(const struct cec_adap_ops *ops, void *priv, const char *name, u32 caps, u8 available_las);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-core.c (0)
Location: drivers/media/cec/cec-core.c:253
Inline: False
```
**Symbols:**

```
ffffffff817e6460-ffffffff817e648d: cec_allocate_adapter.cold (STB_LOCAL)
ffffffff817e5f10-ffffffff817e6141: cec_allocate_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct cec_adapter *cec_allocate_adapter(const struct cec_adap_ops *ops, void *priv, const char *name, u32 caps, u8 available_las);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-core.c (0)
Location: drivers/media/cec/cec-core.c:253
Inline: False
```
**Symbols:**

```
ffffffff8186bd00-ffffffff8186bd2d: cec_allocate_adapter.cold (STB_LOCAL)
ffffffff8186b7b0-ffffffff8186b9e1: cec_allocate_adapter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct cec_adapter *cec_allocate_adapter(const struct cec_adap_ops *ops, void *priv, const char *name, u32 caps, u8 available_las);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-core.c (0)
Location: drivers/media/cec/cec-core.c:253
Inline: False
Direct callers:
  - drivers/media/cec/cec-pin.c:cec_pin_allocate_adapter
```
**Symbols:**

```
ffffffff81885c90-ffffffff81885cbd: cec_allocate_adapter.cold (STB_LOCAL)
ffffffff81885740-ffffffff81885971: cec_allocate_adapter (STB_GLOBAL)
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
