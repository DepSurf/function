# Function: <code>clk_core_forward_rate_req</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void clk_core_forward_rate_req(struct clk_core *core, const struct clk_rate_request *old_req, struct clk_core *parent, struct clk_rate_request *req, long unsigned int parent_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819f8360)
Location: drivers/clk/clk.c:568
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_hw_forward_rate_request
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
**Symbols:**

```
ffffffff819f8360-ffffffff819f8424: clk_core_forward_rate_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void clk_core_forward_rate_req(struct clk_core *core, const struct clk_rate_request *old_req, struct clk_core *parent, struct clk_rate_request *req, long unsigned int parent_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a40c10)
Location: drivers/clk/clk.c:579
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_hw_forward_rate_request
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
**Symbols:**

```
ffffffff81a40c10-ffffffff81a40cd4: clk_core_forward_rate_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void clk_core_forward_rate_req(struct clk_core *core, const struct clk_rate_request *old_req, struct clk_core *parent, struct clk_rate_request *req, long unsigned int parent_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a8c620)
Location: drivers/clk/clk.c:579
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_hw_forward_rate_request
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
**Symbols:**

```
ffffffff81a8c620-ffffffff81a8c6e4: clk_core_forward_rate_req (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
