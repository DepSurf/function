# Function: <code>__cpuidle_unregister_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __cpuidle_unregister_device(struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff816bb3e0)
Location: drivers/cpuidle/cpuidle.c:429
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff816bb3e0-ffffffff816bb44f: __cpuidle_unregister_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __cpuidle_unregister_device(struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff8171cc50)
Location: drivers/cpuidle/cpuidle.c:429
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff8171cc50-ffffffff8171ccc2: __cpuidle_unregister_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __cpuidle_unregister_device(struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff8174f800)
Location: drivers/cpuidle/cpuidle.c:446
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff8174f800-ffffffff8174f872: __cpuidle_unregister_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __cpuidle_unregister_device(struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff8176e2a0)
Location: drivers/cpuidle/cpuidle.c:449
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff8176e2a0-ffffffff8176e30f: __cpuidle_unregister_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __cpuidle_unregister_device(struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff817e3bb0)
Location: drivers/cpuidle/cpuidle.c:455
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff817e3bb0-ffffffff817e3c1f: __cpuidle_unregister_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __cpuidle_unregister_device(struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff8182cdb0)
Location: drivers/cpuidle/cpuidle.c:470
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff8182cdb0-ffffffff8182ce1f: __cpuidle_unregister_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __cpuidle_unregister_device(struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff81858d90)
Location: drivers/cpuidle/cpuidle.c:499
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff81858d90-ffffffff81858dff: __cpuidle_unregister_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __cpuidle_unregister_device(struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff8189c6d0)
Location: drivers/cpuidle/cpuidle.c:513
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff8189c6d0-ffffffff8189c73f: __cpuidle_unregister_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __cpuidle_unregister_device(struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff818ce9f0)
Location: drivers/cpuidle/cpuidle.c:544
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff818ce9f0-ffffffff818cea5f: __cpuidle_unregister_device (STB_LOCAL)
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
In drivers/cpuidle/cpuidle.c (ffffffff819a126b)
Location: drivers/cpuidle/cpuidle.c:547
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
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
In drivers/cpuidle/cpuidle.c (ffffffff819a42bb)
Location: drivers/cpuidle/cpuidle.c:572
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
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
In drivers/cpuidle/cpuidle.c (ffffffff81988ef6)
Location: drivers/cpuidle/cpuidle.c:572
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
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
In drivers/cpuidle/cpuidle.c (ffffffff81a330ef)
Location: drivers/cpuidle/cpuidle.c:572
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
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
In drivers/cpuidle/cpuidle.c (ffffffff81b9f93c)
Location: drivers/cpuidle/cpuidle.c:572
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
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
In drivers/cpuidle/cpuidle.c (ffffffff81d41333)
Location: drivers/cpuidle/cpuidle.c:577
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
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
In drivers/cpuidle/cpuidle.c (ffffffff81dabd03)
Location: drivers/cpuidle/cpuidle.c:609
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
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
In drivers/cpuidle/cpuidle.c (ffffffff81e63da3)
Location: drivers/cpuidle/cpuidle.c:609
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
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
void __cpuidle_unregister_device(struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffff800010b26660)
Location: drivers/cpuidle/cpuidle.c:544
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffff800010b26660-ffff800010b266e4: __cpuidle_unregister_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __cpuidle_unregister_device(struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (c0c013fc)
Location: drivers/cpuidle/cpuidle.c:544
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
c0c013fc-c0c01470: __cpuidle_unregister_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __cpuidle_unregister_device(struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (c000000000c1d510)
Location: drivers/cpuidle/cpuidle.c:544
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
c000000000c1d510-c000000000c1d5cc: __cpuidle_unregister_device (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __cpuidle_unregister_device(struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff818725f0)
Location: drivers/cpuidle/cpuidle.c:544
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff818725f0-ffffffff8187265f: __cpuidle_unregister_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __cpuidle_unregister_device(struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff8183c290)
Location: drivers/cpuidle/cpuidle.c:544
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff8183c290-ffffffff8183c2ff: __cpuidle_unregister_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __cpuidle_unregister_device(struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff818c3ea0)
Location: drivers/cpuidle/cpuidle.c:544
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff818c3ea0-ffffffff818c3f0f: __cpuidle_unregister_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __cpuidle_unregister_device(struct cpuidle_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpuidle/cpuidle.c (ffffffff818e0210)
Location: drivers/cpuidle/cpuidle.c:544
Inline: False
Direct callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_register_device
```
**Symbols:**

```
ffffffff818e0210-ffffffff818e027f: __cpuidle_unregister_device (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
