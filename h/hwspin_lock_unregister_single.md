# Function: <code>hwspin_lock_unregister_single</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct hwspinlock *hwspin_lock_unregister_single(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81811550)
Location: drivers/hwspinlock/hwspinlock_core.c:368
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister
```
**Symbols:**

```
ffffffff81811550-ffffffff818115de: hwspin_lock_unregister_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_unregister_single(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:395
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister
```
**Symbols:**

```
ffffffff8185b3c0-ffffffff8185b425: hwspin_lock_unregister_single (STB_LOCAL)
ffffffff8185bbba-ffffffff8185bbf1: hwspin_lock_unregister_single.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_unregister_single(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:424
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister
```
**Symbols:**

```
ffffffff8187a8a0-ffffffff8187a905: hwspin_lock_unregister_single (STB_LOCAL)
ffffffff8187b2da-ffffffff8187b311: hwspin_lock_unregister_single.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_unregister_single(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:446
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister
```
**Symbols:**

```
ffffffff818bfef0-ffffffff818bff58: hwspin_lock_unregister_single (STB_LOCAL)
ffffffff818c090e-ffffffff818c0947: hwspin_lock_unregister_single.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_unregister_single(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:446
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister
```
**Symbols:**

```
ffffffff818f2a10-ffffffff818f2a78: hwspin_lock_unregister_single (STB_LOCAL)
ffffffff818f33e2-ffffffff818f341b: hwspin_lock_unregister_single.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_unregister_single(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:446
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister
```
**Symbols:**

```
ffffffff819c8350-ffffffff819c83b8: hwspin_lock_unregister_single (STB_LOCAL)
ffffffff819c8d2a-ffffffff819c8d63: hwspin_lock_unregister_single.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_unregister_single(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:446
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister
```
**Symbols:**

```
ffffffff819c80a0-ffffffff819c8108: hwspin_lock_unregister_single (STB_LOCAL)
ffffffff81c2db1e-ffffffff81c2db57: hwspin_lock_unregister_single.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_unregister_single(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:446
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister
```
**Symbols:**

```
ffffffff819acff0-ffffffff819ad058: hwspin_lock_unregister_single (STB_LOCAL)
ffffffff81c1fccd-ffffffff81c1fd06: hwspin_lock_unregister_single.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_unregister_single(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:446
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg
```
**Symbols:**

```
ffffffff81a5b500-ffffffff81a5b568: hwspin_lock_unregister_single (STB_LOCAL)
ffffffff81d3162f-ffffffff81d31668: hwspin_lock_unregister_single.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_unregister_single(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:446
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg
```
**Symbols:**

```
ffffffff81bcb650-ffffffff81bcb6bf: hwspin_lock_unregister_single (STB_LOCAL)
ffffffff81efdaf9-ffffffff81efdb2d: hwspin_lock_unregister_single.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct hwspinlock *hwspin_lock_unregister_single(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81d74ee0)
Location: drivers/hwspinlock/hwspinlock_core.c:446
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg
```
**Symbols:**

```
ffffffff81d74ee0-ffffffff81d74f7a: hwspin_lock_unregister_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct hwspinlock *hwspin_lock_unregister_single(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81de2e20)
Location: drivers/hwspinlock/hwspinlock_core.c:446
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg
```
**Symbols:**

```
ffffffff81de2e20-ffffffff81de2eb8: hwspin_lock_unregister_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct hwspinlock *hwspin_lock_unregister_single(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81e98f10)
Location: drivers/hwspinlock/hwspinlock_core.c:450
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg
```
**Symbols:**

```
ffffffff81e98f10-ffffffff81e98fa8: hwspin_lock_unregister_single (STB_LOCAL)
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
struct hwspinlock *hwspin_lock_unregister_single(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7e2a0)
Location: drivers/hwspinlock/hwspinlock_core.c:446
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister
```
**Symbols:**

```
ffff800010b7e2a0-ffff800010b7e350: hwspin_lock_unregister_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct hwspinlock *hwspin_lock_unregister_single(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (c0c61fe0)
Location: drivers/hwspinlock/hwspinlock_core.c:446
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister
```
**Symbols:**

```
c0c61fe0-c0c62080: hwspin_lock_unregister_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct hwspinlock *hwspin_lock_unregister_single(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (c000000000c5a160)
Location: drivers/hwspinlock/hwspinlock_core.c:446
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister
```
**Symbols:**

```
c000000000c5a160-c000000000c5a248: hwspin_lock_unregister_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct hwspinlock *hwspin_lock_unregister_single(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072c816)
Location: drivers/hwspinlock/hwspinlock_core.c:446
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister
```
**Symbols:**

```
ffffffe00072c816-ffffffe00072c8c8: hwspin_lock_unregister_single (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_unregister_single(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:446
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister
```
**Symbols:**

```
ffffffff81893d40-ffffffff81893da8: hwspin_lock_unregister_single (STB_LOCAL)
ffffffff81894712-ffffffff8189474b: hwspin_lock_unregister_single.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_unregister_single(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:446
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister
```
**Symbols:**

```
ffffffff8184c460-ffffffff8184c4c8: hwspin_lock_unregister_single (STB_LOCAL)
ffffffff8184cbec-ffffffff8184cc25: hwspin_lock_unregister_single.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_unregister_single(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:446
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister
```
**Symbols:**

```
ffffffff818e7840-ffffffff818e78a8: hwspin_lock_unregister_single (STB_LOCAL)
ffffffff818e8212-ffffffff818e824b: hwspin_lock_unregister_single.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_unregister_single(unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:446
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister
```
**Symbols:**

```
ffffffff81904560-ffffffff819045c8: hwspin_lock_unregister_single (STB_LOCAL)
ffffffff81904e7a-ffffffff81904eb3: hwspin_lock_unregister_single.cold (STB_LOCAL)
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
