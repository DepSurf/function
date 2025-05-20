# Function: <code>clk_core_round_rate_nolock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int clk_core_round_rate_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816e43c0)
Location: drivers/clk/clk.c:785
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_round_rate
```
**Symbols:**

```
ffffffff816e43c0-ffffffff816e444f: clk_core_round_rate_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int clk_core_round_rate_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81748780)
Location: drivers/clk/clk.c:836
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_core_round_rate_nolock
```
**Symbols:**

```
ffffffff81748780-ffffffff8174880f: clk_core_round_rate_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int clk_core_round_rate_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81531000)
Location: drivers/clk/clk.c:836
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_core_round_rate_nolock
```
**Symbols:**

```
ffffffff81531000-ffffffff8153108f: clk_core_round_rate_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int clk_core_round_rate_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81544510)
Location: drivers/clk/clk.c:836
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_core_round_rate_nolock
```
**Symbols:**

```
ffffffff81544510-ffffffff8154459f: clk_core_round_rate_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int clk_core_round_rate_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815a75e0)
Location: drivers/clk/clk.c:909
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_core_round_rate_nolock
```
**Symbols:**

```
ffffffff815a75e0-ffffffff815a7675: clk_core_round_rate_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int clk_core_round_rate_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815e1000)
Location: drivers/clk/clk.c:1128
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
**Symbols:**

```
ffffffff815e1000-ffffffff815e1075: clk_core_round_rate_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int clk_core_round_rate_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815fb270)
Location: drivers/clk/clk.c:1234
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
**Symbols:**

```
ffffffff815fb270-ffffffff815fb2e5: clk_core_round_rate_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int clk_core_round_rate_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162d6e0)
Location: drivers/clk/clk.c:1352
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
**Symbols:**

```
ffffffff8162d6e0-ffffffff8162d764: clk_core_round_rate_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int clk_core_round_rate_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8164e3d0)
Location: drivers/clk/clk.c:1360
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
**Symbols:**

```
ffffffff8164e3d0-ffffffff8164e454: clk_core_round_rate_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int clk_core_round_rate_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fd240)
Location: drivers/clk/clk.c:1364
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
**Symbols:**

```
ffffffff816fd240-ffffffff816fd2c4: clk_core_round_rate_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int clk_core_round_rate_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8171a1f0)
Location: drivers/clk/clk.c:1358
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
**Symbols:**

```
ffffffff8171a1f0-ffffffff8171a274: clk_core_round_rate_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int clk_core_round_rate_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fb4f0)
Location: drivers/clk/clk.c:1379
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
**Symbols:**

```
ffffffff816fb4f0-ffffffff816fb574: clk_core_round_rate_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int clk_core_round_rate_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81775e60)
Location: drivers/clk/clk.c:1379
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
**Symbols:**

```
ffffffff81775e60-ffffffff81775eeb: clk_core_round_rate_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int clk_core_round_rate_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818ac680)
Location: drivers/clk/clk.c:1393
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
**Symbols:**

```
ffffffff818ac680-ffffffff818ac727: clk_core_round_rate_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int clk_core_round_rate_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819f8540)
Location: drivers/clk/clk.c:1545
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
**Symbols:**

```
ffffffff819f8540-ffffffff819f86b2: clk_core_round_rate_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int clk_core_round_rate_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a40e50)
Location: drivers/clk/clk.c:1590
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
**Symbols:**

```
ffffffff81a40e50-ffffffff81a40fc9: clk_core_round_rate_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int clk_core_round_rate_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a8c860)
Location: drivers/clk/clk.c:1590
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_core_round_rate_nolock
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
**Symbols:**

```
ffffffff81a8c860-ffffffff81a8c9d9: clk_core_round_rate_nolock (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int clk_core_round_rate_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107bd950)
Location: drivers/clk/clk.c:1360
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
**Symbols:**

```
ffff8000107bd950-ffff8000107bd9f4: clk_core_round_rate_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int clk_core_round_rate_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08ea6ac)
Location: drivers/clk/clk.c:1360
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
**Symbols:**

```
c08ea6ac-c08ea740: clk_core_round_rate_nolock (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int clk_core_round_rate_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050ce72)
Location: drivers/clk/clk.c:1360
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
**Symbols:**

```
ffffffe00050ce72-ffffffe00050cefc: clk_core_round_rate_nolock (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int clk_core_round_rate_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81614430)
Location: drivers/clk/clk.c:1360
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
**Symbols:**

```
ffffffff81614430-ffffffff816144b4: clk_core_round_rate_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int clk_core_round_rate_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81608960)
Location: drivers/clk/clk.c:1360
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
**Symbols:**

```
ffffffff81608960-ffffffff816089e4: clk_core_round_rate_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int clk_core_round_rate_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81642210)
Location: drivers/clk/clk.c:1360
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
**Symbols:**

```
ffffffff81642210-ffffffff81642294: clk_core_round_rate_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int clk_core_round_rate_nolock(struct clk_core *core, struct clk_rate_request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165c5f0)
Location: drivers/clk/clk.c:1360
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_round_rate
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
```
**Symbols:**

```
ffffffff8165c5f0-ffffffff8165c674: clk_core_round_rate_nolock (STB_LOCAL)
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
