# Function: <code>clk_core_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int clk_core_enable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816e6cf0)
Location: drivers/clk/clk.c:721
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_enable
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:__clk_set_parent_before
```
**Symbols:**

```
ffffffff816e6cf0-ffffffff816e6e21: clk_core_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int clk_core_enable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8174aec0)
Location: drivers/clk/clk.c:643
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_enable
```
**Symbols:**

```
ffffffff8174aec0-ffffffff8174b001: clk_core_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int clk_core_enable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81533740)
Location: drivers/clk/clk.c:643
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_enable
```
**Symbols:**

```
ffffffff81533740-ffffffff81533881: clk_core_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int clk_core_enable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81546480)
Location: drivers/clk/clk.c:643
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable_lock
```
**Symbols:**

```
ffffffff81546480-ffffffff815465c4: clk_core_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int clk_core_enable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815a97a0)
Location: drivers/clk/clk.c:706
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable_lock
```
**Symbols:**

```
ffffffff815a97a0-ffffffff815a98f4: clk_core_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int clk_core_enable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815dfd30)
Location: drivers/clk/clk.c:864
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_enable
```
**Symbols:**

```
ffffffff815dfd30-ffffffff815dfe79: clk_core_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int clk_core_enable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815f9c00)
Location: drivers/clk/clk.c:875
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_enable
```
**Symbols:**

```
ffffffff815f9c00-ffffffff815f9db6: clk_core_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int clk_core_enable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162bfb0)
Location: drivers/clk/clk.c:996
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_enable
```
**Symbols:**

```
ffffffff8162bfb0-ffffffff8162c166: clk_core_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int clk_core_enable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8164d560)
Location: drivers/clk/clk.c:1004
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_enable
```
**Symbols:**

```
ffffffff8164d560-ffffffff8164d716: clk_core_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int clk_core_enable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816ffd90)
Location: drivers/clk/clk.c:1008
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_core_enable
```
**Symbols:**

```
ffffffff816ffd90-ffffffff816fff46: clk_core_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int clk_core_enable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8171d0e0)
Location: drivers/clk/clk.c:1002
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_core_enable
```
**Symbols:**

```
ffffffff8171d0e0-ffffffff8171d26e: clk_core_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int clk_core_enable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fdf10)
Location: drivers/clk/clk.c:1002
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_core_enable
```
**Symbols:**

```
ffffffff816fdf10-ffffffff816fe09e: clk_core_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int clk_core_enable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81777840)
Location: drivers/clk/clk.c:1002
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_core_enable
```
**Symbols:**

```
ffffffff81777840-ffffffff817779cb: clk_core_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int clk_core_enable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818addc0)
Location: drivers/clk/clk.c:1014
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_core_enable
```
**Symbols:**

```
ffffffff818addc0-ffffffff818adf78: clk_core_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int clk_core_enable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819f9630)
Location: drivers/clk/clk.c:1098
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_core_enable
```
**Symbols:**

```
ffffffff819f9630-ffffffff819f97e8: clk_core_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int clk_core_enable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a41ea0)
Location: drivers/clk/clk.c:1140
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_core_enable
```
**Symbols:**

```
ffffffff81a41ea0-ffffffff81a41fce: clk_core_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int clk_core_enable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a8d8b0)
Location: drivers/clk/clk.c:1140
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_core_enable
```
**Symbols:**

```
ffffffff81a8d8b0-ffffffff81a8d9de: clk_core_enable (STB_LOCAL)
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
int clk_core_enable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107c0f60)
Location: drivers/clk/clk.c:1004
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_enable
```
**Symbols:**

```
ffff8000107c0f60-ffff8000107c1184: clk_core_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int clk_core_enable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08ead2c)
Location: drivers/clk/clk.c:1004
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_enable
```
**Symbols:**

```
c08ead2c-c08eafb4: clk_core_enable (STB_LOCAL)
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
int clk_core_enable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050b42a)
Location: drivers/clk/clk.c:1004
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_enable
```
**Symbols:**

```
ffffffe00050b42a-ffffffe00050b5ec: clk_core_enable (STB_LOCAL)
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
int clk_core_enable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816135c0)
Location: drivers/clk/clk.c:1004
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_enable
```
**Symbols:**

```
ffffffff816135c0-ffffffff81613776: clk_core_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int clk_core_enable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81607af0)
Location: drivers/clk/clk.c:1004
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_enable
```
**Symbols:**

```
ffffffff81607af0-ffffffff81607ca6: clk_core_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int clk_core_enable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816413a0)
Location: drivers/clk/clk.c:1004
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_enable
```
**Symbols:**

```
ffffffff816413a0-ffffffff81641556: clk_core_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int clk_core_enable(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165b750)
Location: drivers/clk/clk.c:1004
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_enable
```
**Symbols:**

```
ffffffff8165b750-ffffffff8165b93b: clk_core_enable (STB_LOCAL)
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
