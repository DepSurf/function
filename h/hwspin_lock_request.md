# Function: <code>hwspin_lock_request</code>

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
struct hwspinlock *hwspin_lock_request();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818119f0)
Location: drivers/hwspinlock/hwspinlock_core.c:547
Inline: False
```
**Symbols:**

```
ffffffff818119f0-ffffffff81811a97: hwspin_lock_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_request();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:574
Inline: False
```
**Symbols:**

```
ffffffff8185bbf1-ffffffff8185bc11: hwspin_lock_request.cold.8 (STB_LOCAL)
ffffffff8185b5b0-ffffffff8185b63e: hwspin_lock_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_request();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:685
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
```
**Symbols:**

```
ffffffff8187b311-ffffffff8187b331: hwspin_lock_request.cold.12 (STB_LOCAL)
ffffffff8187aab0-ffffffff8187ab3e: hwspin_lock_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_request();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:707
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
```
**Symbols:**

```
ffffffff818c0ab6-ffffffff818c0ae9: hwspin_lock_request.cold (STB_LOCAL)
ffffffff818c03c0-ffffffff818c044e: hwspin_lock_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_request();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:707
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
```
**Symbols:**

```
ffffffff818f3518-ffffffff818f3538: hwspin_lock_request.cold (STB_LOCAL)
ffffffff818f2ec0-ffffffff818f2f4e: hwspin_lock_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_request();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:709
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
```
**Symbols:**

```
ffffffff819c8dff-ffffffff819c8e1f: hwspin_lock_request.cold (STB_LOCAL)
ffffffff819c8680-ffffffff819c870e: hwspin_lock_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_request();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:709
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
```
**Symbols:**

```
ffffffff81c2dbf3-ffffffff81c2dc13: hwspin_lock_request.cold (STB_LOCAL)
ffffffff819c83d0-ffffffff819c845e: hwspin_lock_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_request();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:709
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
```
**Symbols:**

```
ffffffff81c1fda2-ffffffff81c1fdc2: hwspin_lock_request.cold (STB_LOCAL)
ffffffff819ad320-ffffffff819ad3ae: hwspin_lock_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_request();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:709
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
```
**Symbols:**

```
ffffffff81d31704-ffffffff81d31724: hwspin_lock_request.cold (STB_LOCAL)
ffffffff81a5b870-ffffffff81a5b8fe: hwspin_lock_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_request();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:709
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
```
**Symbols:**

```
ffffffff81efdbc9-ffffffff81efdbe7: hwspin_lock_request.cold (STB_LOCAL)
ffffffff81bcba40-ffffffff81bcbae5: hwspin_lock_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct hwspinlock *hwspin_lock_request();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81d753f0)
Location: drivers/hwspinlock/hwspinlock_core.c:709
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
```
**Symbols:**

```
ffffffff81d753f0-ffffffff81d754b0: hwspin_lock_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct hwspinlock *hwspin_lock_request();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81de3330)
Location: drivers/hwspinlock/hwspinlock_core.c:709
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
```
**Symbols:**

```
ffffffff81de3330-ffffffff81de33f0: hwspin_lock_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct hwspinlock *hwspin_lock_request();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81e99420)
Location: drivers/hwspinlock/hwspinlock_core.c:714
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
```
**Symbols:**

```
ffffffff81e99420-ffffffff81e994e0: hwspin_lock_request (STB_GLOBAL)
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
struct hwspinlock *hwspin_lock_request();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7ea28)
Location: drivers/hwspinlock/hwspinlock_core.c:707
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
```
**Symbols:**

```
ffff800010b7ea28-ffff800010b7eae8: hwspin_lock_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct hwspinlock *hwspin_lock_request();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (c0c626a8)
Location: drivers/hwspinlock/hwspinlock_core.c:707
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
```
**Symbols:**

```
c0c626a8-c0c6278c: hwspin_lock_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct hwspinlock *hwspin_lock_request();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (c000000000c5a580)
Location: drivers/hwspinlock/hwspinlock_core.c:707
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
```
**Symbols:**

```
c000000000c5a580-c000000000c5a670: hwspin_lock_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct hwspinlock *hwspin_lock_request();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072ca70)
Location: drivers/hwspinlock/hwspinlock_core.c:707
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
```
**Symbols:**

```
ffffffe00072ca70-ffffffe00072cb08: hwspin_lock_request (STB_GLOBAL)
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
struct hwspinlock *hwspin_lock_request();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:707
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
```
**Symbols:**

```
ffffffff81894848-ffffffff81894868: hwspin_lock_request.cold (STB_LOCAL)
ffffffff818941f0-ffffffff8189427e: hwspin_lock_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_request();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:707
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
```
**Symbols:**

```
ffffffff8184cd22-ffffffff8184cd42: hwspin_lock_request.cold (STB_LOCAL)
ffffffff8184c910-ffffffff8184c99e: hwspin_lock_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_request();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:707
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
```
**Symbols:**

```
ffffffff818e8348-ffffffff818e8368: hwspin_lock_request.cold (STB_LOCAL)
ffffffff818e7cf0-ffffffff818e7d7e: hwspin_lock_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct hwspinlock *hwspin_lock_request();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:707
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_request
```
**Symbols:**

```
ffffffff81904fb0-ffffffff81904fd0: hwspin_lock_request.cold (STB_LOCAL)
ffffffff81904a10-ffffffff81904a9e: hwspin_lock_request (STB_GLOBAL)
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
