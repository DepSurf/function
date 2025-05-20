# Function: <code>clk_core_enable_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int clk_core_enable_lock(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8174b010)
Location: drivers/clk/clk.c:678
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_enable
```
**Symbols:**

```
ffffffff8174b010-ffffffff8174b040: clk_core_enable_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int clk_core_enable_lock(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81533890)
Location: drivers/clk/clk.c:678
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_enable
```
**Symbols:**

```
ffffffff81533890-ffffffff815338c0: clk_core_enable_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int clk_core_enable_lock(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815465d0)
Location: drivers/clk/clk.c:678
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_set_parent_before
```
**Symbols:**

```
ffffffff815465d0-ffffffff81546600: clk_core_enable_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int clk_core_enable_lock(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815a9900)
Location: drivers/clk/clk.c:741
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_set_parent_before
```
**Symbols:**

```
ffffffff815a9900-ffffffff815a9930: clk_core_enable_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int clk_core_enable_lock(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815dfe80)
Location: drivers/clk/clk.c:900
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_set_parent_before
```
**Symbols:**

```
ffffffff815dfe80-ffffffff815dfeb0: clk_core_enable_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int clk_core_enable_lock(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815f9dc0)
Location: drivers/clk/clk.c:911
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_set_parent_before
```
**Symbols:**

```
ffffffff815f9dc0-ffffffff815f9df0: clk_core_enable_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int clk_core_enable_lock(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162c170)
Location: drivers/clk/clk.c:1032
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_set_parent_before
```
**Symbols:**

```
ffffffff8162c170-ffffffff8162c1a4: clk_core_enable_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int clk_core_enable_lock(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8164e390)
Location: drivers/clk/clk.c:1040
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_set_parent_before
```
**Symbols:**

```
ffffffff8164e390-ffffffff8164e3c4: clk_core_enable_lock (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff81700479)
Location: drivers/clk/clk.c:1044
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_set_parent_before
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
In drivers/clk/clk.c (ffffffff8171d9b9)
Location: drivers/clk/clk.c:1038
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_set_parent_before
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
In drivers/clk/clk.c (ffffffff816ff1b2)
Location: drivers/clk/clk.c:1038
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
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
In drivers/clk/clk.c (ffffffff81779a83)
Location: drivers/clk/clk.c:1038
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
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
In drivers/clk/clk.c (ffffffff818afda5)
Location: drivers/clk/clk.c:1050
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
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
In drivers/clk/clk.c (ffffffff819fc0f9)
Location: drivers/clk/clk.c:1134
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
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
In drivers/clk/clk.c (ffffffff81a44b9e)
Location: drivers/clk/clk.c:1176
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
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
In drivers/clk/clk.c (ffffffff81a906ae)
Location: drivers/clk/clk.c:1176
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
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
int clk_core_enable_lock(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107c1188)
Location: drivers/clk/clk.c:1040
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_set_parent_before
```
**Symbols:**

```
ffff8000107c1188-ffff8000107c11cc: clk_core_enable_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int clk_core_enable_lock(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08eafb4)
Location: drivers/clk/clk.c:1040
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_set_parent_before
```
**Symbols:**

```
c08eafb4-c08eaff0: clk_core_enable_lock (STB_LOCAL)
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
int clk_core_enable_lock(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050ce2c)
Location: drivers/clk/clk.c:1040
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_set_parent_before
```
**Symbols:**

```
ffffffe00050ce2c-ffffffe00050ce72: clk_core_enable_lock (STB_LOCAL)
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
int clk_core_enable_lock(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816143f0)
Location: drivers/clk/clk.c:1040
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_set_parent_before
```
**Symbols:**

```
ffffffff816143f0-ffffffff81614424: clk_core_enable_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int clk_core_enable_lock(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81608920)
Location: drivers/clk/clk.c:1040
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_set_parent_before
```
**Symbols:**

```
ffffffff81608920-ffffffff81608954: clk_core_enable_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int clk_core_enable_lock(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816421d0)
Location: drivers/clk/clk.c:1040
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_set_parent_before
```
**Symbols:**

```
ffffffff816421d0-ffffffff81642204: clk_core_enable_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int clk_core_enable_lock(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165c5b0)
Location: drivers/clk/clk.c:1040
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_set_parent_before
```
**Symbols:**

```
ffffffff8165c5b0-ffffffff8165c5e4: clk_core_enable_lock (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
