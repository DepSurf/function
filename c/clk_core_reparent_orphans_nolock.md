# Function: <code>clk_core_reparent_orphans_nolock</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81651be6)
Location: drivers/clk/clk.c:3234
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void clk_core_reparent_orphans_nolock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff817009d0)
Location: drivers/clk/clk.c:3307
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
```
**Symbols:**

```
ffffffff817009d0-ffffffff81700a78: clk_core_reparent_orphans_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void clk_core_reparent_orphans_nolock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8171def0)
Location: drivers/clk/clk.c:3358
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
```
**Symbols:**

```
ffffffff8171def0-ffffffff8171df98: clk_core_reparent_orphans_nolock (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff816ff1d6)
Location: drivers/clk/clk.c:3371
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
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
In drivers/clk/clk.c (ffffffff81779aa5)
Location: drivers/clk/clk.c:3389
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
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
In drivers/clk/clk.c (ffffffff818afdc9)
Location: drivers/clk/clk.c:3451
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
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
In drivers/clk/clk.c (ffffffff819fc11d)
Location: drivers/clk/clk.c:3641
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
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
In drivers/clk/clk.c (ffffffff81a44bc2)
Location: drivers/clk/clk.c:3686
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
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
In drivers/clk/clk.c (ffffffff81a906d2)
Location: drivers/clk/clk.c:3732
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
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
void clk_core_reparent_orphans_nolock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107c1950)
Location: drivers/clk/clk.c:3234
Inline: False
Direct callers:
  - drivers/clk/clk.c:of_clk_add_hw_provider
  - drivers/clk/clk.c:of_clk_add_hw_provider
  - drivers/clk/clk.c:of_clk_add_provider
  - drivers/clk/clk.c:of_clk_add_provider
  - drivers/clk/clk.c:__clk_core_init
```
**Symbols:**

```
ffff8000107c1950-ffff8000107c19e0: clk_core_reparent_orphans_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void clk_core_reparent_orphans_nolock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08ec580)
Location: drivers/clk/clk.c:3234
Inline: False
Direct callers:
  - drivers/clk/clk.c:of_clk_add_hw_provider
  - drivers/clk/clk.c:of_clk_add_provider
  - drivers/clk/clk.c:__clk_core_init
```
**Symbols:**

```
c08ec580-c08ec60c: clk_core_reparent_orphans_nolock (STB_LOCAL)
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
void clk_core_reparent_orphans_nolock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050f620)
Location: drivers/clk/clk.c:3234
Inline: False
Direct callers:
  - drivers/clk/clk.c:of_clk_add_hw_provider
  - drivers/clk/clk.c:of_clk_add_provider
  - drivers/clk/clk.c:__clk_core_init
```
**Symbols:**

```
ffffffe00050f620-ffffffe00050f6a6: clk_core_reparent_orphans_nolock (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff81617c46)
Location: drivers/clk/clk.c:3234
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
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
In drivers/clk/clk.c (ffffffff8160c176)
Location: drivers/clk/clk.c:3234
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
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
In drivers/clk/clk.c (ffffffff81645a26)
Location: drivers/clk/clk.c:3234
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
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
In drivers/clk/clk.c (ffffffff8165ffb6)
Location: drivers/clk/clk.c:3234
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
