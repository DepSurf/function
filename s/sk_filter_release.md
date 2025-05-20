# Function: <code>sk_filter_release</code>

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
In net/core/filter.c (ffffffff81732afb)
Location: net/core/filter.c:902
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
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
In net/core/filter.c (ffffffff8179e41b)
Location: net/core/filter.c:926
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
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
In net/core/filter.c (ffffffff817cce7b)
Location: net/core/filter.c:928
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817ec2ab)
Location: net/core/filter.c:946
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_uncharge
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sk_filter_release(struct sk_filter *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81863a60)
Location: net/core/filter.c:965
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
```
**Symbols:**

```
ffffffff81863a60-ffffffff81863a88: sk_filter_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sk_filter_release(struct sk_filter *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b15f0)
Location: net/core/filter.c:1174
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
```
**Symbols:**

```
ffffffff818b15f0-ffffffff818b1618: sk_filter_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sk_filter_release(struct sk_filter *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d6130)
Location: net/core/filter.c:1176
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
```
**Symbols:**

```
ffffffff818d6130-ffffffff818d6158: sk_filter_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void sk_filter_release(struct sk_filter *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81925780)
Location: net/core/filter.c:1176
Inline: True
Direct callers:
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
```
**Symbols:**

```
ffffffff81925780-ffffffff819257a7: sk_filter_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void sk_filter_release(struct sk_filter *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81957bb0)
Location: net/core/filter.c:1176
Inline: True
Direct callers:
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
```
**Symbols:**

```
ffffffff81957bb0-ffffffff81957bd7: sk_filter_release (STB_LOCAL)
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
In net/core/filter.c (ffffffff81a3238d)
Location: net/core/filter.c:1165
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In net/core/filter.c (ffffffff81a346cd)
Location: net/core/filter.c:1195
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In net/core/filter.c (ffffffff81a1b739)
Location: net/core/filter.c:1195
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In net/core/filter.c (ffffffff81acee19)
Location: net/core/filter.c:1196
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In net/core/filter.c (ffffffff81c4c4da)
Location: net/core/filter.c:1197
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
  - net/core/filter.c:sk_filter_uncharge
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
In net/core/filter.c (ffffffff81e0128a)
Location: net/core/filter.c:1199
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
  - net/core/filter.c:sk_filter_uncharge
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
In net/core/filter.c (ffffffff81e72d46)
Location: net/core/filter.c:1199
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
  - net/core/filter.c:sk_filter_uncharge
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
In net/core/filter.c (ffffffff81f324ba)
Location: net/core/filter.c:1204
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
  - net/core/filter.c:sk_filter_uncharge
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
void sk_filter_release(struct sk_filter *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bf7950)
Location: net/core/filter.c:1176
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
  - net/core/filter.c:sk_filter_uncharge
```
**Symbols:**

```
ffff800010bf7950-ffff800010bf79a0: sk_filter_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sk_filter_release(struct sk_filter *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d10c78)
Location: net/core/filter.c:1176
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
```
**Symbols:**

```
c0d10c78-c0d10cb0: sk_filter_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sk_filter_release(struct sk_filter *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cdd7f0)
Location: net/core/filter.c:1176
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
```
**Symbols:**

```
c000000000cdd7f0-c000000000cdd854: sk_filter_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe000781876)
Location: net/core/filter.c:1176
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
void sk_filter_release(struct sk_filter *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f7b80)
Location: net/core/filter.c:1176
Inline: True
Direct callers:
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
```
**Symbols:**

```
ffffffff818f7b80-ffffffff818f7ba7: sk_filter_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void sk_filter_release(struct sk_filter *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b19b0)
Location: net/core/filter.c:1176
Inline: True
Direct callers:
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
```
**Symbols:**

```
ffffffff818b19b0-ffffffff818b19d7: sk_filter_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void sk_filter_release(struct sk_filter *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81948bb0)
Location: net/core/filter.c:1176
Inline: True
Direct callers:
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
```
**Symbols:**

```
ffffffff81948bb0-ffffffff81948bd7: sk_filter_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void sk_filter_release(struct sk_filter *fp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196a4c0)
Location: net/core/filter.c:1176
Inline: True
Direct callers:
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
```
**Symbols:**

```
ffffffff8196a4c0-ffffffff8196a4e7: sk_filter_release (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
