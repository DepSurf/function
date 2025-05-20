# Function: <code>__napi_gro_flush_chain</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b6fa7)
Location: net/core/dev.c:5380
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81902da8)
Location: net/core/dev.c:5390
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81935b27)
Location: net/core/dev.c:5313
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0a80c)
Location: net/core/dev.c:5696
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0ba22)
Location: net/core/dev.c:5797
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819f1f72)
Location: net/core/dev.c:5919
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa388b)
Location: net/core/dev.c:5889
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/gro.c (ffffffff81c53fcc)
Location: net/core/gro.c:318
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/gro.c (ffffffff81e096dc)
Location: net/core/gro.c:329
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/gro.c (ffffffff81e7beac)
Location: net/core/gro.c:272
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/gro.c (ffffffff81f3c1fc)
Location: net/core/gro.c:272
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_flush
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
void __napi_gro_flush_chain(struct napi_struct *napi, u32 index, bool flush_old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd3ef0)
Location: net/core/dev.c:5313
Inline: False
Direct callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_complete_done
```
**Symbols:**

```
ffff800010bd3ef0-ffff800010bd3ff8: __napi_gro_flush_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __napi_gro_flush_chain(struct napi_struct *napi, u32 index, bool flush_old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cef708)
Location: net/core/dev.c:5313
Inline: False
Direct callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_complete_done
```
**Symbols:**

```
c0cef708-c0cef804: __napi_gro_flush_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __napi_gro_flush_chain(struct napi_struct *napi, u32 index, bool flush_old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb2d90)
Location: net/core/dev.c:5313
Inline: False
Direct callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:napi_complete_done
```
**Symbols:**

```
c000000000cb2d90-c000000000cb2f08: __napi_gro_flush_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075df82)
Location: net/core/dev.c:5313
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_flush
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d5af7)
Location: net/core/dev.c:5313
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188f967)
Location: net/core/dev.c:5313
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81926b27)
Location: net/core/dev.c:5313
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81948177)
Location: net/core/dev.c:5313
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_flush
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
