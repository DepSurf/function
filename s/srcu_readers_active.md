# Function: <code>srcu_readers_active</code>

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
In kernel/rcu/srcu.c (ffffffff810e3b16)
Location: kernel/rcu/srcu.c:263
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:cleanup_srcu_struct
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810e9e26)
Location: kernel/rcu/srcu.c:263
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:cleanup_srcu_struct
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810f0cfd)
Location: kernel/rcu/srcu.c:263
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:cleanup_srcu_struct
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810f0cd0)
Location: kernel/rcu/srcutree.c:311
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
**Symbols:**

```
ffffffff810f0cd0-ffffffff810f0d4e: srcu_readers_active.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810fab90)
Location: kernel/rcu/srcutree.c:312
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
**Symbols:**

```
ffffffff810fab90-ffffffff810fabfe: srcu_readers_active.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81103010)
Location: kernel/rcu/srcutree.c:339
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:_cleanup_srcu_struct
  - kernel/rcu/srcutree.c:_cleanup_srcu_struct
```
**Symbols:**

```
ffffffff81103010-ffffffff8110307e: srcu_readers_active.isra.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110e9c0)
Location: kernel/rcu/srcutree.c:344
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:_cleanup_srcu_struct
  - kernel/rcu/srcutree.c:_cleanup_srcu_struct
```
**Symbols:**

```
ffffffff8110e9c0-ffffffff8110ea2e: srcu_readers_active.isra.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811180a0)
Location: kernel/rcu/srcutree.c:333
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
**Symbols:**

```
ffffffff811180a0-ffffffff81118106: srcu_readers_active.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81124460)
Location: kernel/rcu/srcutree.c:333
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
**Symbols:**

```
ffffffff81124460-ffffffff811244c6: srcu_readers_active.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool srcu_readers_active(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81131bb0)
Location: kernel/rcu/srcutree.c:346
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
**Symbols:**

```
ffffffff81131bb0-ffffffff81131c1a: srcu_readers_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool srcu_readers_active(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112d390)
Location: kernel/rcu/srcutree.c:335
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
**Symbols:**

```
ffffffff8112d390-ffffffff8112d3fa: srcu_readers_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool srcu_readers_active(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112d9a0)
Location: kernel/rcu/srcutree.c:338
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
**Symbols:**

```
ffffffff8112d9a0-ffffffff8112da12: srcu_readers_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool srcu_readers_active(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8114ec50)
Location: kernel/rcu/srcutree.c:330
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
**Symbols:**

```
ffffffff8114ec50-ffffffff8114ecf9: srcu_readers_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool srcu_readers_active(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81175920)
Location: kernel/rcu/srcutree.c:498
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
**Symbols:**

```
ffffffff81175920-ffffffff811759d5: srcu_readers_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool srcu_readers_active(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811ad430)
Location: kernel/rcu/srcutree.c:503
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
**Symbols:**

```
ffffffff811ad430-ffffffff811ad4f5: srcu_readers_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool srcu_readers_active(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811bf380)
Location: kernel/rcu/srcutree.c:547
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_module_notify
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
**Symbols:**

```
ffffffff811bf380-ffffffff811bf442: srcu_readers_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool srcu_readers_active(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811cf7f0)
Location: kernel/rcu/srcutree.c:549
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_module_notify
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
**Symbols:**

```
ffffffff811cf7f0-ffffffff811cf8b2: srcu_readers_active (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffff800010189968)
Location: kernel/rcu/srcutree.c:333
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
**Symbols:**

```
ffff800010189968-ffff800010189a08: srcu_readers_active.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool srcu_readers_active(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c03d80dc)
Location: kernel/rcu/srcutree.c:333
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
**Symbols:**

```
c03d80dc-c03d8164: srcu_readers_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool srcu_readers_active(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c0000000001e3db0)
Location: kernel/rcu/srcutree.c:333
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
**Symbols:**

```
c0000000001e3db0-c0000000001e3e7c: srcu_readers_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool srcu_readers_active(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffe00011ea46)
Location: kernel/rcu/srcutree.c:333
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
**Symbols:**

```
ffffffe00011ea46-ffffffe00011ead0: srcu_readers_active (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111ca40)
Location: kernel/rcu/srcutree.c:333
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
**Symbols:**

```
ffffffff8111ca40-ffffffff8111caa6: srcu_readers_active.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110db00)
Location: kernel/rcu/srcutree.c:333
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
**Symbols:**

```
ffffffff8110db00-ffffffff8110db66: srcu_readers_active.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111a930)
Location: kernel/rcu/srcutree.c:333
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
**Symbols:**

```
ffffffff8111a930-ffffffff8111a996: srcu_readers_active.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81126210)
Location: kernel/rcu/srcutree.c:333
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
```
**Symbols:**

```
ffffffff81126210-ffffffff81126276: srcu_readers_active.isra.0 (STB_LOCAL)
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
</ul>
