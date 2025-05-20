# Function: <code>hte_request_ts_ns</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hte_request_ts_ns(struct hte_ts_desc *desc, hte_ts_cb_t cb, hte_ts_sec_cb_t tcb, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hte/hte.c (0)
Location: drivers/hte/hte.c:656
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:hte_edge_setup
```
**Symbols:**

```
ffffffff81f00e61-ffffffff81f00e8a: hte_request_ts_ns.cold (STB_LOCAL)
ffffffff81be51c0-ffffffff81be5235: hte_request_ts_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hte_request_ts_ns(struct hte_ts_desc *desc, hte_ts_cb_t cb, hte_ts_sec_cb_t tcb, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hte/hte.c (ffffffff81d91350)
Location: drivers/hte/hte.c:656
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:hte_edge_setup
```
**Symbols:**

```
ffffffff81d91350-ffffffff81d913f7: hte_request_ts_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hte_request_ts_ns(struct hte_ts_desc *desc, hte_ts_cb_t cb, hte_ts_sec_cb_t tcb, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hte/hte.c (ffffffff81dff620)
Location: drivers/hte/hte.c:656
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:hte_edge_setup
```
**Symbols:**

```
ffffffff81dff620-ffffffff81dff6c7: hte_request_ts_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hte_request_ts_ns(struct hte_ts_desc *desc, hte_ts_cb_t cb, hte_ts_sec_cb_t tcb, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hte/hte.c (ffffffff81eb5d50)
Location: drivers/hte/hte.c:651
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:hte_edge_setup
```
**Symbols:**

```
ffffffff81eb5d50-ffffffff81eb5df7: hte_request_ts_ns (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
