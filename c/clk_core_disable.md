# Function: <code>clk_core_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void clk_core_disable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816e6b60)
Location: drivers/clk/clk.c:673
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_core_enable
```
**Symbols:**

```
ffffffff816e6b60-ffffffff816e6c5a: clk_core_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void clk_core_disable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8174acb0)
Location: drivers/clk/clk.c:587
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable_lock
```
**Symbols:**

```
ffffffff8174acb0-ffffffff8174adcf: clk_core_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void clk_core_disable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81533530)
Location: drivers/clk/clk.c:587
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable_lock
```
**Symbols:**

```
ffffffff81533530-ffffffff8153364f: clk_core_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void clk_core_disable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81544ba0)
Location: drivers/clk/clk.c:587
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_disable_lock
  - drivers/clk/clk.c:clk_core_disable
```
**Symbols:**

```
ffffffff81544ba0-ffffffff81544cc2: clk_core_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void clk_core_disable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815a7f10)
Location: drivers/clk/clk.c:650
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_disable_lock
  - drivers/clk/clk.c:clk_core_disable
```
**Symbols:**

```
ffffffff815a7f10-ffffffff815a8044: clk_core_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void clk_core_disable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815dfba0)
Location: drivers/clk/clk.c:807
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable_lock
  - drivers/clk/clk.c:clk_core_disable
```
**Symbols:**

```
ffffffff815dfba0-ffffffff815dfcd0: clk_core_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void clk_core_disable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815f99f0)
Location: drivers/clk/clk.c:818
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable_lock
  - drivers/clk/clk.c:clk_core_disable
```
**Symbols:**

```
ffffffff815f99f0-ffffffff815f9b96: clk_core_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void clk_core_disable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162bda0)
Location: drivers/clk/clk.c:939
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable_lock
  - drivers/clk/clk.c:clk_core_disable
```
**Symbols:**

```
ffffffff8162bda0-ffffffff8162bf46: clk_core_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void clk_core_disable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8164d3b0)
Location: drivers/clk/clk.c:947
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable_lock
  - drivers/clk/clk.c:clk_core_disable
```
**Symbols:**

```
ffffffff8164d3b0-ffffffff8164d556: clk_core_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void clk_core_disable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816ffa30)
Location: drivers/clk/clk.c:951
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_disable
  - drivers/clk/clk.c:clk_core_disable
```
**Symbols:**

```
ffffffff816ffa30-ffffffff816ffbd1: clk_core_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void clk_core_disable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8171cdb0)
Location: drivers/clk/clk.c:945
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_disable
  - drivers/clk/clk.c:clk_core_disable
```
**Symbols:**

```
ffffffff8171cdb0-ffffffff8171cf27: clk_core_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void clk_core_disable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fd400)
Location: drivers/clk/clk.c:945
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_disable
  - drivers/clk/clk.c:clk_core_disable
```
**Symbols:**

```
ffffffff816fd400-ffffffff816fd577: clk_core_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void clk_core_disable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81776e90)
Location: drivers/clk/clk.c:945
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_disable
  - drivers/clk/clk.c:clk_core_disable
```
**Symbols:**

```
ffffffff81776e90-ffffffff81777001: clk_core_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void clk_core_disable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818ad760)
Location: drivers/clk/clk.c:957
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_disable
  - drivers/clk/clk.c:clk_core_disable
```
**Symbols:**

```
ffffffff818ad760-ffffffff818ad931: clk_core_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void clk_core_disable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819f9000)
Location: drivers/clk/clk.c:1041
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_disable
  - drivers/clk/clk.c:clk_core_disable
```
**Symbols:**

```
ffffffff819f9000-ffffffff819f91d4: clk_core_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void clk_core_disable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a416e0)
Location: drivers/clk/clk.c:1083
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_disable
  - drivers/clk/clk.c:clk_core_disable
```
**Symbols:**

```
ffffffff81a416e0-ffffffff81a4181f: clk_core_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void clk_core_disable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a8d0f0)
Location: drivers/clk/clk.c:1083
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_disable
  - drivers/clk/clk.c:clk_core_disable
```
**Symbols:**

```
ffffffff81a8d0f0-ffffffff81a8d22f: clk_core_disable (STB_LOCAL)
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
void clk_core_disable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107c0850)
Location: drivers/clk/clk.c:947
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable_lock
  - drivers/clk/clk.c:clk_core_disable
```
**Symbols:**

```
ffff8000107c0850-ffff8000107c0a54: clk_core_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void clk_core_disable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08eaa3c)
Location: drivers/clk/clk.c:947
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable_lock
```
**Symbols:**

```
c08eaa3c-c08eacc8: clk_core_disable (STB_LOCAL)
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
void clk_core_disable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050b24e)
Location: drivers/clk/clk.c:947
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable_lock
  - drivers/clk/clk.c:clk_core_disable
```
**Symbols:**

```
ffffffe00050b24e-ffffffe00050b42a: clk_core_disable (STB_LOCAL)
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
void clk_core_disable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81613410)
Location: drivers/clk/clk.c:947
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable_lock
  - drivers/clk/clk.c:clk_core_disable
```
**Symbols:**

```
ffffffff81613410-ffffffff816135b6: clk_core_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void clk_core_disable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81607940)
Location: drivers/clk/clk.c:947
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable_lock
  - drivers/clk/clk.c:clk_core_disable
```
**Symbols:**

```
ffffffff81607940-ffffffff81607ae6: clk_core_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void clk_core_disable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816411f0)
Location: drivers/clk/clk.c:947
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable_lock
  - drivers/clk/clk.c:clk_core_disable
```
**Symbols:**

```
ffffffff816411f0-ffffffff81641396: clk_core_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void clk_core_disable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165b570)
Location: drivers/clk/clk.c:947
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable_lock
  - drivers/clk/clk.c:clk_core_disable
```
**Symbols:**

```
ffffffff8165b570-ffffffff8165b74f: clk_core_disable (STB_LOCAL)
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
