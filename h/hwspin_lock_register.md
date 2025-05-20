# Function: <code>hwspin_lock_register</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int hwspin_lock_register(struct hwspinlock_device *bank, struct device *dev, const struct hwspinlock_ops *ops, int base_id, int num_locks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818117b0)
Location: drivers/hwspinlock/hwspinlock_core.c:408
Inline: True
```
**Symbols:**

```
ffffffff818117b0-ffffffff818118e2: hwspin_lock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hwspin_lock_register(struct hwspinlock_device *bank, struct device *dev, const struct hwspinlock_ops *ops, int base_id, int num_locks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:435
Inline: True
```
**Symbols:**

```
ffffffff8185bc84-ffffffff8185bcbc: hwspin_lock_register.cold.12 (STB_LOCAL)
ffffffff8185b820-ffffffff8185b913: hwspin_lock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hwspin_lock_register(struct hwspinlock_device *bank, struct device *dev, const struct hwspinlock_ops *ops, int base_id, int num_locks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8187aea0)
Location: drivers/hwspinlock/hwspinlock_core.c:464
Inline: True
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
**Symbols:**

```
ffffffff8187b3a4-ffffffff8187b3dc: hwspin_lock_register.cold.16 (STB_LOCAL)
ffffffff8187ae40-ffffffff8187af31: hwspin_lock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int hwspin_lock_register(struct hwspinlock_device *bank, struct device *dev, const struct hwspinlock_ops *ops, int base_id, int num_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:486
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
**Symbols:**

```
ffffffff818c0947-ffffffff818c0992: hwspin_lock_register.cold (STB_LOCAL)
ffffffff818bff60-ffffffff818c0047: hwspin_lock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int hwspin_lock_register(struct hwspinlock_device *bank, struct device *dev, const struct hwspinlock_ops *ops, int base_id, int num_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:486
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
**Symbols:**

```
ffffffff818f341b-ffffffff818f3453: hwspin_lock_register.cold (STB_LOCAL)
ffffffff818f2a80-ffffffff818f2b66: hwspin_lock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int hwspin_lock_register(struct hwspinlock_device *bank, struct device *dev, const struct hwspinlock_ops *ops, int base_id, int num_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:486
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
**Symbols:**

```
ffffffff819c8d63-ffffffff819c8d9b: hwspin_lock_register.cold (STB_LOCAL)
ffffffff819c83c0-ffffffff819c84a6: hwspin_lock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int hwspin_lock_register(struct hwspinlock_device *bank, struct device *dev, const struct hwspinlock_ops *ops, int base_id, int num_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:486
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
**Symbols:**

```
ffffffff81c2db57-ffffffff81c2db8f: hwspin_lock_register.cold (STB_LOCAL)
ffffffff819c8110-ffffffff819c81f6: hwspin_lock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int hwspin_lock_register(struct hwspinlock_device *bank, struct device *dev, const struct hwspinlock_ops *ops, int base_id, int num_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:486
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
**Symbols:**

```
ffffffff81c1fd06-ffffffff81c1fd3e: hwspin_lock_register.cold (STB_LOCAL)
ffffffff819ad060-ffffffff819ad146: hwspin_lock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hwspin_lock_register(struct hwspinlock_device *bank, struct device *dev, const struct hwspinlock_ops *ops, int base_id, int num_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:486
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
**Symbols:**

```
ffffffff81d31668-ffffffff81d316a0: hwspin_lock_register.cold (STB_LOCAL)
ffffffff81a5b570-ffffffff81a5b656: hwspin_lock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hwspin_lock_register(struct hwspinlock_device *bank, struct device *dev, const struct hwspinlock_ops *ops, int base_id, int num_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:486
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
**Symbols:**

```
ffffffff81efdb2d-ffffffff81efdb65: hwspin_lock_register.cold (STB_LOCAL)
ffffffff81bcb6c0-ffffffff81bcb7b5: hwspin_lock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hwspin_lock_register(struct hwspinlock_device *bank, struct device *dev, const struct hwspinlock_ops *ops, int base_id, int num_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81d74f90)
Location: drivers/hwspinlock/hwspinlock_core.c:486
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
**Symbols:**

```
ffffffff81d74f90-ffffffff81d750b7: hwspin_lock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hwspin_lock_register(struct hwspinlock_device *bank, struct device *dev, const struct hwspinlock_ops *ops, int base_id, int num_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81de2ed0)
Location: drivers/hwspinlock/hwspinlock_core.c:486
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
**Symbols:**

```
ffffffff81de2ed0-ffffffff81de2ff7: hwspin_lock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hwspin_lock_register(struct hwspinlock_device *bank, struct device *dev, const struct hwspinlock_ops *ops, int base_id, int num_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81e98fc0)
Location: drivers/hwspinlock/hwspinlock_core.c:490
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
**Symbols:**

```
ffffffff81e98fc0-ffffffff81e990e7: hwspin_lock_register (STB_GLOBAL)
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
int hwspin_lock_register(struct hwspinlock_device *bank, struct device *dev, const struct hwspinlock_ops *ops, int base_id, int num_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7e350)
Location: drivers/hwspinlock/hwspinlock_core.c:486
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
**Symbols:**

```
ffff800010b7e350-ffff800010b7e4bc: hwspin_lock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hwspin_lock_register(struct hwspinlock_device *bank, struct device *dev, const struct hwspinlock_ops *ops, int base_id, int num_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (c0c62080)
Location: drivers/hwspinlock/hwspinlock_core.c:486
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
**Symbols:**

```
c0c62080-c0c621d0: hwspin_lock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int hwspin_lock_register(struct hwspinlock_device *bank, struct device *dev, const struct hwspinlock_ops *ops, int base_id, int num_locks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (c000000000c5ae60)
Location: drivers/hwspinlock/hwspinlock_core.c:486
Inline: True
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
**Symbols:**

```
c000000000c5ae60-c000000000c5b06c: hwspin_lock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int hwspin_lock_register(struct hwspinlock_device *bank, struct device *dev, const struct hwspinlock_ops *ops, int base_id, int num_locks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072ce9c)
Location: drivers/hwspinlock/hwspinlock_core.c:486
Inline: True
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
**Symbols:**

```
ffffffe00072ce9c-ffffffe00072cfdc: hwspin_lock_register (STB_GLOBAL)
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
int hwspin_lock_register(struct hwspinlock_device *bank, struct device *dev, const struct hwspinlock_ops *ops, int base_id, int num_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:486
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
**Symbols:**

```
ffffffff8189474b-ffffffff81894783: hwspin_lock_register.cold (STB_LOCAL)
ffffffff81893db0-ffffffff81893e96: hwspin_lock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int hwspin_lock_register(struct hwspinlock_device *bank, struct device *dev, const struct hwspinlock_ops *ops, int base_id, int num_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:486
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
**Symbols:**

```
ffffffff8184cc25-ffffffff8184cc5d: hwspin_lock_register.cold (STB_LOCAL)
ffffffff8184c4d0-ffffffff8184c5b6: hwspin_lock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int hwspin_lock_register(struct hwspinlock_device *bank, struct device *dev, const struct hwspinlock_ops *ops, int base_id, int num_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:486
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
**Symbols:**

```
ffffffff818e824b-ffffffff818e8283: hwspin_lock_register.cold (STB_LOCAL)
ffffffff818e78b0-ffffffff818e7996: hwspin_lock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int hwspin_lock_register(struct hwspinlock_device *bank, struct device *dev, const struct hwspinlock_ops *ops, int base_id, int num_locks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:486
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_register
```
**Symbols:**

```
ffffffff81904eb3-ffffffff81904eeb: hwspin_lock_register.cold (STB_LOCAL)
ffffffff819045d0-ffffffff819046b6: hwspin_lock_register (STB_GLOBAL)
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
