# Function: <code>clk_core_rate_protect</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void clk_core_rate_protect(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815df9ed)
Location: drivers/clk/clk.c:619
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_rate_range
Direct callers:
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_rate_range
```
**Symbols:**

```
ffffffff815df260-ffffffff815df2a4: clk_core_rate_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void clk_core_rate_protect(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815f9926)
Location: drivers/clk/clk.c:617
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
ffffffff815f8b80-ffffffff815f8bc4: clk_core_rate_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void clk_core_rate_protect(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162bcd6)
Location: drivers/clk/clk.c:738
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
ffffffff8162adb0-ffffffff8162adf4: clk_core_rate_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void clk_core_rate_protect(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8164efa6)
Location: drivers/clk/clk.c:746
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
ffffffff8164c860-ffffffff8164c8a4: clk_core_rate_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void clk_core_rate_protect(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81701d60)
Location: drivers/clk/clk.c:750
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
ffffffff816fff90-ffffffff81700005: clk_core_rate_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void clk_core_rate_protect(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8171f0a0)
Location: drivers/clk/clk.c:744
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
ffffffff8171d2b0-ffffffff8171d325: clk_core_rate_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void clk_core_rate_protect(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816ffcf0)
Location: drivers/clk/clk.c:744
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
ffffffff816fe340-ffffffff816fe3b5: clk_core_rate_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void clk_core_rate_protect(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8177a4f0)
Location: drivers/clk/clk.c:744
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
ffffffff81778b30-ffffffff81778ba5: clk_core_rate_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void clk_core_rate_protect(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818b0b74)
Location: drivers/clk/clk.c:756
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
ffffffff818af020-ffffffff818af0ad: clk_core_rate_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void clk_core_rate_protect(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819fda74)
Location: drivers/clk/clk.c:841
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
ffffffff819fab50-ffffffff819fabdd: clk_core_rate_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void clk_core_rate_protect(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a45c12)
Location: drivers/clk/clk.c:883
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
ffffffff81a42ff0-ffffffff81a4307d: clk_core_rate_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void clk_core_rate_protect(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a91702)
Location: drivers/clk/clk.c:883
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_round_rate
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
ffffffff81a8eb00-ffffffff81a8eb8d: clk_core_rate_protect (STB_LOCAL)
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
void clk_core_rate_protect(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107c0210)
Location: drivers/clk/clk.c:746
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
ffff8000107bb798-ffff8000107bb7e0: clk_core_rate_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void clk_core_rate_protect(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08e9f0c)
Location: drivers/clk/clk.c:746
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
c08e7508-c08e754c: clk_core_rate_protect (STB_LOCAL)
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
void clk_core_rate_protect(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050ca8c)
Location: drivers/clk/clk.c:746
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
ffffffe00050a54a-ffffffe00050a588: clk_core_rate_protect (STB_LOCAL)
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
void clk_core_rate_protect(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81615006)
Location: drivers/clk/clk.c:746
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
ffffffff816128c0-ffffffff81612904: clk_core_rate_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void clk_core_rate_protect(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81609536)
Location: drivers/clk/clk.c:746
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
ffffffff81606e10-ffffffff81606e54: clk_core_rate_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void clk_core_rate_protect(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81642de6)
Location: drivers/clk/clk.c:746
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
ffffffff816406a0-ffffffff816406e4: clk_core_rate_protect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void clk_core_rate_protect(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165d226)
Location: drivers/clk/clk.c:746
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_prepare
Direct callers:
  - drivers/clk/clk.c:clk_set_duty_cycle
  - drivers/clk/clk.c:clk_set_phase
  - drivers/clk/clk.c:clk_set_rate_range
  - drivers/clk/clk.c:clk_core_prepare
```
**Symbols:**

```
ffffffff8165a9f0-ffffffff8165aa34: clk_core_rate_protect (STB_LOCAL)
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
