# Function: <code>clk_core_init_rate_req</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void clk_core_init_rate_req(const struct clk_core * core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815df2b0)
Location: drivers/clk/clk.c:1102
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff815df2b0-ffffffff815df2f2: clk_core_init_rate_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void clk_core_init_rate_req(const struct clk_core * core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815f8d70)
Location: drivers/clk/clk.c:1208
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff815f8d70-ffffffff815f8db2: clk_core_init_rate_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void clk_core_init_rate_req(const struct clk_core * core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:1329
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff8162b7f0-ffffffff8162b838: clk_core_init_rate_req (STB_LOCAL)
ffffffff81630e51-ffffffff81630e64: clk_core_init_rate_req.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void clk_core_init_rate_req(const struct clk_core * core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8164d210)
Location: drivers/clk/clk.c:1337
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff8164d210-ffffffff8164d254: clk_core_init_rate_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void clk_core_init_rate_req(const struct clk_core * core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fc020)
Location: drivers/clk/clk.c:1341
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff816fc020-ffffffff816fc064: clk_core_init_rate_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void clk_core_init_rate_req(const struct clk_core * core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81718f20)
Location: drivers/clk/clk.c:1335
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff81718f20-ffffffff81718f64: clk_core_init_rate_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void clk_core_init_rate_req(const struct clk_core * core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fa220)
Location: drivers/clk/clk.c:1356
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff816fa220-ffffffff816fa264: clk_core_init_rate_req (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff81777e66)
Location: drivers/clk/clk.c:1356
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
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
In drivers/clk/clk.c (ffffffff818ae175)
Location: drivers/clk/clk.c:1370
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_core_round_rate_nolock
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void clk_core_init_rate_req(const struct clk_core * core, struct clk_rate_request *req, long unsigned int rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819f58b0)
Location: drivers/clk/clk.c:1466
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_hw_init_rate_request
  - drivers/clk/clk.c:clk_core_forward_rate_req
```
**Symbols:**

```
ffffffff819f58b0-ffffffff819f5956: clk_core_init_rate_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void clk_core_init_rate_req(const struct clk_core * core, struct clk_rate_request *req, long unsigned int rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a3e030)
Location: drivers/clk/clk.c:1510
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_hw_init_rate_request
  - drivers/clk/clk.c:clk_core_forward_rate_req
```
**Symbols:**

```
ffffffff81a3e030-ffffffff81a3e0d6: clk_core_init_rate_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void clk_core_init_rate_req(const struct clk_core * core, struct clk_rate_request *req, long unsigned int rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a89920)
Location: drivers/clk/clk.c:1510
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_hw_init_rate_request
  - drivers/clk/clk.c:clk_core_forward_rate_req
```
**Symbols:**

```
ffffffff81a89920-ffffffff81a899c6: clk_core_init_rate_req (STB_LOCAL)
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
void clk_core_init_rate_req(const struct clk_core * core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107bbfe0)
Location: drivers/clk/clk.c:1337
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffff8000107bbfe0-ffff8000107bc04c: clk_core_init_rate_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void clk_core_init_rate_req(const struct clk_core * core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08e848c)
Location: drivers/clk/clk.c:1337
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
c08e848c-c08e84f4: clk_core_init_rate_req (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void clk_core_init_rate_req(const struct clk_core * core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050af86)
Location: drivers/clk/clk.c:1337
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffe00050af86-ffffffe00050afe2: clk_core_init_rate_req (STB_LOCAL)
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
void clk_core_init_rate_req(const struct clk_core * core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81613270)
Location: drivers/clk/clk.c:1337
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff81613270-ffffffff816132b4: clk_core_init_rate_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void clk_core_init_rate_req(const struct clk_core * core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816077a0)
Location: drivers/clk/clk.c:1337
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff816077a0-ffffffff816077e4: clk_core_init_rate_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void clk_core_init_rate_req(const struct clk_core * core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81641050)
Location: drivers/clk/clk.c:1337
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff81641050-ffffffff81641094: clk_core_init_rate_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void clk_core_init_rate_req(const struct clk_core * core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165b250)
Location: drivers/clk/clk.c:1337
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_calc_new_rates
```
**Symbols:**

```
ffffffff8165b250-ffffffff8165b294: clk_core_init_rate_req (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
