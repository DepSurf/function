# Function: <code>__clk_init_parent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816e871d)
Location: drivers/clk/clk.c:1671
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct clk_core *__clk_init_parent(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81749ee0)
Location: drivers/clk/clk.c:1728
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
```
**Symbols:**

```
ffffffff81749ee0-ffffffff81749f23: __clk_init_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct clk_core *__clk_init_parent(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81532760)
Location: drivers/clk/clk.c:1728
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
```
**Symbols:**

```
ffffffff81532760-ffffffff815327a3: __clk_init_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct clk_core *__clk_init_parent(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81545920)
Location: drivers/clk/clk.c:1730
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
```
**Symbols:**

```
ffffffff81545920-ffffffff81545956: __clk_init_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct clk_core *__clk_init_parent(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815a8ea0)
Location: drivers/clk/clk.c:1841
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
```
**Symbols:**

```
ffffffff815a8ea0-ffffffff815a8ed9: __clk_init_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct clk_core *__clk_init_parent(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815e0850)
Location: drivers/clk/clk.c:2139
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
```
**Symbols:**

```
ffffffff815e0850-ffffffff815e0889: __clk_init_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct clk_core *__clk_init_parent(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815fa880)
Location: drivers/clk/clk.c:2252
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_register
```
**Symbols:**

```
ffffffff815fa880-ffffffff815fa8b9: __clk_init_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct clk_core *__clk_init_parent(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162cb20)
Location: drivers/clk/clk.c:2388
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
```
**Symbols:**

```
ffffffff8162cb20-ffffffff8162cb5b: __clk_init_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct clk_core *__clk_init_parent(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8164dff0)
Location: drivers/clk/clk.c:2396
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
```
**Symbols:**

```
ffffffff8164dff0-ffffffff8164e02b: __clk_init_parent (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff81700b8d)
Location: drivers/clk/clk.c:2417
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_core_reparent_orphans_nolock
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
In drivers/clk/clk.c (ffffffff8171e0ad)
Location: drivers/clk/clk.c:2432
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_core_reparent_orphans_nolock
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
In drivers/clk/clk.c (ffffffff816ff085)
Location: drivers/clk/clk.c:2445
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
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
In drivers/clk/clk.c (ffffffff81779935)
Location: drivers/clk/clk.c:2445
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
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
In drivers/clk/clk.c (ffffffff818afc67)
Location: drivers/clk/clk.c:2462
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
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
In drivers/clk/clk.c (ffffffff819fbf4b)
Location: drivers/clk/clk.c:2666
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
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
In drivers/clk/clk.c (ffffffff81a449f7)
Location: drivers/clk/clk.c:2711
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
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
In drivers/clk/clk.c (ffffffff81a90507)
Location: drivers/clk/clk.c:2711
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
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
struct clk_core *__clk_init_parent(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107bd260)
Location: drivers/clk/clk.c:2396
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_core_reparent_orphans_nolock
```
**Symbols:**

```
ffff8000107bd260-ffff8000107bd2b8: __clk_init_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk_core *__clk_init_parent(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08e9318)
Location: drivers/clk/clk.c:2396
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_core_reparent_orphans_nolock
```
**Symbols:**

```
c08e9318-c08e9368: __clk_init_parent (STB_LOCAL)
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
struct clk_core *__clk_init_parent(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050c65e)
Location: drivers/clk/clk.c:2396
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_core_reparent_orphans_nolock
```
**Symbols:**

```
ffffffe00050c65e-ffffffe00050c6a2: __clk_init_parent (STB_LOCAL)
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
struct clk_core *__clk_init_parent(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81614050)
Location: drivers/clk/clk.c:2396
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
```
**Symbols:**

```
ffffffff81614050-ffffffff8161408b: __clk_init_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct clk_core *__clk_init_parent(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81608580)
Location: drivers/clk/clk.c:2396
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
```
**Symbols:**

```
ffffffff81608580-ffffffff816085bb: __clk_init_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct clk_core *__clk_init_parent(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81641e30)
Location: drivers/clk/clk.c:2396
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
```
**Symbols:**

```
ffffffff81641e30-ffffffff81641e6b: __clk_init_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct clk_core *__clk_init_parent(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165c210)
Location: drivers/clk/clk.c:2396
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
```
**Symbols:**

```
ffffffff8165c210-ffffffff8165c24b: __clk_init_parent (STB_LOCAL)
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
