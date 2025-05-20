# Function: <code>__hte_req_ts</code>

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
int __hte_req_ts(struct hte_ts_desc *desc, hte_ts_cb_t cb, hte_ts_sec_cb_t tcb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hte/hte.c (0)
Location: drivers/hte/hte.c:354
Inline: False
Direct callers:
  - drivers/hte/hte.c:hte_request_ts_ns
```
**Symbols:**

```
ffffffff81be4fb0-ffffffff81be51ba: __hte_req_ts (STB_LOCAL)
ffffffff81f00e47-ffffffff81f00e61: __hte_req_ts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __hte_req_ts(struct hte_ts_desc *desc, hte_ts_cb_t cb, hte_ts_sec_cb_t tcb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hte/hte.c (ffffffff81d91120)
Location: drivers/hte/hte.c:354
Inline: False
Direct callers:
  - drivers/hte/hte.c:hte_request_ts_ns
```
**Symbols:**

```
ffffffff81d91120-ffffffff81d9133f: __hte_req_ts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __hte_req_ts(struct hte_ts_desc *desc, hte_ts_cb_t cb, hte_ts_sec_cb_t tcb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hte/hte.c (ffffffff81dff3f0)
Location: drivers/hte/hte.c:354
Inline: False
Direct callers:
  - drivers/hte/hte.c:hte_request_ts_ns
```
**Symbols:**

```
ffffffff81dff3f0-ffffffff81dff60f: __hte_req_ts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __hte_req_ts(struct hte_ts_desc *desc, hte_ts_cb_t cb, hte_ts_sec_cb_t tcb, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hte/hte.c (ffffffff81eb5b40)
Location: drivers/hte/hte.c:352
Inline: False
Direct callers:
  - drivers/hte/hte.c:hte_request_ts_ns
```
**Symbols:**

```
ffffffff81eb5b40-ffffffff81eb5d3b: __hte_req_ts (STB_LOCAL)
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
