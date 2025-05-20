# Function: <code>propagate_protected_usage</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
void propagate_protected_usage(struct page_counter *c, long unsigned int usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8127e280)
Location: mm/page_counter.c:16
Inline: False
Direct callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
**Symbols:**

```
ffffffff8127e280-ffffffff8127e301: propagate_protected_usage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void propagate_protected_usage(struct page_counter *c, long unsigned int usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff81292970)
Location: mm/page_counter.c:16
Inline: False
Direct callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
**Symbols:**

```
ffffffff81292970-ffffffff812929f1: propagate_protected_usage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void propagate_protected_usage(struct page_counter *c, long unsigned int usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812ad340)
Location: mm/page_counter.c:16
Inline: False
Direct callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
**Symbols:**

```
ffffffff812ad340-ffffffff812ad3c0: propagate_protected_usage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void propagate_protected_usage(struct page_counter *c, long unsigned int usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812bee90)
Location: mm/page_counter.c:16
Inline: False
Direct callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
**Symbols:**

```
ffffffff812bee90-ffffffff812bef10: propagate_protected_usage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void propagate_protected_usage(struct page_counter *c, long unsigned int usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812f4170)
Location: mm/page_counter.c:16
Inline: False
Direct callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_uncharge
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
**Symbols:**

```
ffffffff812f4170-ffffffff812f41e2: propagate_protected_usage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void propagate_protected_usage(struct page_counter *c, long unsigned int usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812ffa60)
Location: mm/page_counter.c:16
Inline: False
Direct callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_uncharge
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
**Symbols:**

```
ffffffff812ffa60-ffffffff812ffad2: propagate_protected_usage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void propagate_protected_usage(struct page_counter *c, long unsigned int usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff81306700)
Location: mm/page_counter.c:16
Inline: False
Direct callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
  - mm/page_counter.c:page_counter_cancel
```
**Symbols:**

```
ffffffff81306700-ffffffff81306775: propagate_protected_usage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void propagate_protected_usage(struct page_counter *c, long unsigned int usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff81350530)
Location: mm/page_counter.c:16
Inline: False
Direct callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
  - mm/page_counter.c:page_counter_cancel
```
**Symbols:**

```
ffffffff81350530-ffffffff813505a5: propagate_protected_usage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void propagate_protected_usage(struct page_counter *c, long unsigned int usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff813c87e0)
Location: mm/page_counter.c:16
Inline: False
Direct callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
  - mm/page_counter.c:page_counter_cancel
```
**Symbols:**

```
ffffffff813c87e0-ffffffff813c8863: propagate_protected_usage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void propagate_protected_usage(struct page_counter *c, long unsigned int usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff8144cea0)
Location: mm/page_counter.c:16
Inline: False
Direct callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
  - mm/page_counter.c:page_counter_cancel
```
**Symbols:**

```
ffffffff8144cea0-ffffffff8144cf26: propagate_protected_usage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void propagate_protected_usage(struct page_counter *c, long unsigned int usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff81482760)
Location: mm/page_counter.c:16
Inline: False
Direct callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
  - mm/page_counter.c:page_counter_cancel
```
**Symbols:**

```
ffffffff81482760-ffffffff814827e6: propagate_protected_usage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void propagate_protected_usage(struct page_counter *c, long unsigned int usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff814b1ae0)
Location: mm/page_counter.c:16
Inline: False
Direct callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
  - mm/page_counter.c:page_counter_cancel
```
**Symbols:**

```
ffffffff814b1ae0-ffffffff814b1b66: propagate_protected_usage (STB_LOCAL)
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
void propagate_protected_usage(struct page_counter *c, long unsigned int usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffff800010360970)
Location: mm/page_counter.c:16
Inline: False
Direct callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
**Symbols:**

```
ffff800010360970-ffff800010360a80: propagate_protected_usage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void propagate_protected_usage(struct page_counter *c, long unsigned int usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (c05530f4)
Location: mm/page_counter.c:16
Inline: False
Direct callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
**Symbols:**

```
c05530f4-c05531f4: propagate_protected_usage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void propagate_protected_usage(struct page_counter *c, long unsigned int usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (c00000000044bab0)
Location: mm/page_counter.c:16
Inline: False
Direct callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
**Symbols:**

```
c00000000044bab0-c00000000044bbe8: propagate_protected_usage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void propagate_protected_usage(struct page_counter *c, long unsigned int usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffe000240298)
Location: mm/page_counter.c:16
Inline: False
Direct callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
**Symbols:**

```
ffffffe000240298-ffffffe000240322: propagate_protected_usage (STB_LOCAL)
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
void propagate_protected_usage(struct page_counter *c, long unsigned int usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812b7470)
Location: mm/page_counter.c:16
Inline: False
Direct callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
**Symbols:**

```
ffffffff812b7470-ffffffff812b74f0: propagate_protected_usage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void propagate_protected_usage(struct page_counter *c, long unsigned int usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812a8640)
Location: mm/page_counter.c:16
Inline: False
Direct callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
**Symbols:**

```
ffffffff812a8640-ffffffff812a86c0: propagate_protected_usage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void propagate_protected_usage(struct page_counter *c, long unsigned int usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812b5280)
Location: mm/page_counter.c:16
Inline: False
Direct callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
**Symbols:**

```
ffffffff812b5280-ffffffff812b5300: propagate_protected_usage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void propagate_protected_usage(struct page_counter *c, long unsigned int usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_counter.c (ffffffff812c57c0)
Location: mm/page_counter.c:16
Inline: False
Direct callers:
  - mm/page_counter.c:page_counter_set_low
  - mm/page_counter.c:page_counter_set_min
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_try_charge
  - mm/page_counter.c:page_counter_charge
```
**Symbols:**

```
ffffffff812c57c0-ffffffff812c5840: propagate_protected_usage (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
