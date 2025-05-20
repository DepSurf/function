# Function: <code>__x2apic_send_IPI_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask *mask, int vector, int apic_dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810597f0)
Location: arch/x86/kernel/apic/x2apic_phys.c:40
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059c20)
Location: arch/x86/kernel/apic/x2apic_cluster.c:27
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask
```
**Symbols:**

```
ffffffff810597f0-ffffffff810598c3: __x2apic_send_IPI_mask (STB_LOCAL)
ffffffff81059c20-ffffffff81059d8a: __x2apic_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask *mask, int vector, int apic_dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059a70)
Location: arch/x86/kernel/apic/x2apic_phys.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059ef0)
Location: arch/x86/kernel/apic/x2apic_cluster.c:35
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask
```
**Symbols:**

```
ffffffff81059a70-ffffffff81059b1f: __x2apic_send_IPI_mask (STB_LOCAL)
ffffffff81059ef0-ffffffff8105a035: __x2apic_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask *mask, int vector, int apic_dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c820)
Location: arch/x86/kernel/apic/x2apic_phys.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105ccb0)
Location: arch/x86/kernel/apic/x2apic_cluster.c:35
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask
```
**Symbols:**

```
ffffffff8105c820-ffffffff8105c8d8: __x2apic_send_IPI_mask (STB_LOCAL)
ffffffff8105ccb0-ffffffff8105cdfa: __x2apic_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask *mask, int vector, int apic_dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105bf30)
Location: arch/x86/kernel/apic/x2apic_phys.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c620)
Location: arch/x86/kernel/apic/x2apic_cluster.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask
```
**Symbols:**

```
ffffffff8105bf30-ffffffff8105bfe8: __x2apic_send_IPI_mask (STB_LOCAL)
ffffffff8105c620-ffffffff8105c768: __x2apic_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask *mask, int vector, int apic_dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81060000)
Location: arch/x86/kernel/apic/x2apic_phys.c:50
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81060350)
Location: arch/x86/kernel/apic/x2apic_cluster.c:39
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask
```
**Symbols:**

```
ffffffff81060000-ffffffff810600c7: __x2apic_send_IPI_mask (STB_LOCAL)
ffffffff81060350-ffffffff8106047f: __x2apic_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask *mask, int vector, int apic_dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81062fe0)
Location: arch/x86/kernel/apic/x2apic_phys.c:50
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81063440)
Location: arch/x86/kernel/apic/x2apic_cluster.c:39
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask
```
**Symbols:**

```
ffffffff81062fe0-ffffffff810630a3: __x2apic_send_IPI_mask (STB_LOCAL)
ffffffff81063440-ffffffff8106356f: __x2apic_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask *mask, int vector, int apic_dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81068dc0)
Location: arch/x86/kernel/apic/x2apic_phys.c:50
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81069140)
Location: arch/x86/kernel/apic/x2apic_cluster.c:39
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask
```
**Symbols:**

```
ffffffff81068dc0-ffffffff81068e83: __x2apic_send_IPI_mask (STB_LOCAL)
ffffffff81069140-ffffffff8106926f: __x2apic_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask *mask, int vector, int apic_dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106c5f0)
Location: arch/x86/kernel/apic/x2apic_phys.c:50
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106c990)
Location: arch/x86/kernel/apic/x2apic_cluster.c:39
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask
```
**Symbols:**

```
ffffffff8106c5f0-ffffffff8106c6b1: __x2apic_send_IPI_mask (STB_LOCAL)
ffffffff8106c990-ffffffff8106cab3: __x2apic_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask *mask, int vector, int apic_dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106dcf0)
Location: arch/x86/kernel/apic/x2apic_phys.c:45
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106e130)
Location: arch/x86/kernel/apic/x2apic_cluster.c:37
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask
```
**Symbols:**

```
ffffffff8106dcf0-ffffffff8106ddb1: __x2apic_send_IPI_mask (STB_LOCAL)
ffffffff8106e130-ffffffff8106e253: __x2apic_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask *mask, int vector, int apic_dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075170)
Location: arch/x86/kernel/apic/x2apic_phys.c:45
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810757b0)
Location: arch/x86/kernel/apic/x2apic_cluster.c:37
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask
```
**Symbols:**

```
ffffffff81075170-ffffffff81075231: __x2apic_send_IPI_mask (STB_LOCAL)
ffffffff810757b0-ffffffff810758d3: __x2apic_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask *mask, int vector, int apic_dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810757a0)
Location: arch/x86/kernel/apic/x2apic_phys.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075df0)
Location: arch/x86/kernel/apic/x2apic_cluster.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask
```
**Symbols:**

```
ffffffff810757a0-ffffffff81075864: __x2apic_send_IPI_mask (STB_LOCAL)
ffffffff81075df0-ffffffff81075f11: __x2apic_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask *mask, int vector, int apic_dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81076270)
Location: arch/x86/kernel/apic/x2apic_phys.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81076870)
Location: arch/x86/kernel/apic/x2apic_cluster.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask
```
**Symbols:**

```
ffffffff81076270-ffffffff81076347: __x2apic_send_IPI_mask (STB_LOCAL)
ffffffff81076870-ffffffff810769af: __x2apic_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask *mask, int vector, int apic_dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81083870)
Location: arch/x86/kernel/apic/x2apic_phys.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81083fe0)
Location: arch/x86/kernel/apic/x2apic_cluster.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask
```
**Symbols:**

```
ffffffff81083870-ffffffff81083961: __x2apic_send_IPI_mask (STB_LOCAL)
ffffffff81083fe0-ffffffff81084180: __x2apic_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask *mask, int vector, int apic_dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81093830)
Location: arch/x86/kernel/apic/x2apic_phys.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810940e0)
Location: arch/x86/kernel/apic/x2apic_cluster.c:44
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask
```
**Symbols:**

```
ffffffff81093830-ffffffff81093928: __x2apic_send_IPI_mask (STB_LOCAL)
ffffffff810940e0-ffffffff81094242: __x2apic_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask *mask, int vector, int apic_dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810a8f60)
Location: arch/x86/kernel/apic/x2apic_phys.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a9710)
Location: arch/x86/kernel/apic/x2apic_cluster.c:44
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask
```
**Symbols:**

```
ffffffff810a8f60-ffffffff810a906c: __x2apic_send_IPI_mask (STB_LOCAL)
ffffffff810a9710-ffffffff810a988d: __x2apic_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Transformation ⚠️</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask *mask, int vector, int apic_dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810ac180)
Location: arch/x86/kernel/apic/x2apic_phys.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: arch/x86/kernel/apic/x2apic_cluster.c:39
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask
```
**Symbols:**

```
ffffffff810ac180-ffffffff810ac28c: __x2apic_send_IPI_mask (STB_LOCAL)
ffffffff810ac920-ffffffff810acae3: __x2apic_send_IPI_mask (STB_LOCAL)
ffffffff820d25c2-ffffffff820d25dd: __x2apic_send_IPI_mask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Transformation ⚠️</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask *mask, int vector, int apic_dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810b2f20)
Location: arch/x86/kernel/apic/x2apic_phys.c:54
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (0)
Location: arch/x86/kernel/apic/x2apic_cluster.c:39
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask
```
**Symbols:**

```
ffffffff810b2f20-ffffffff810b302b: __x2apic_send_IPI_mask (STB_LOCAL)
ffffffff810b35a0-ffffffff810b3763: __x2apic_send_IPI_mask (STB_LOCAL)
ffffffff821ad2f2-ffffffff821ad30d: __x2apic_send_IPI_mask.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask *mask, int vector, int apic_dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cc90)
Location: arch/x86/kernel/apic/x2apic_phys.c:45
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d0d0)
Location: arch/x86/kernel/apic/x2apic_cluster.c:37
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask
```
**Symbols:**

```
ffffffff8106cc90-ffffffff8106cd51: __x2apic_send_IPI_mask (STB_LOCAL)
ffffffff8106d0d0-ffffffff8106d1f3: __x2apic_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask *mask, int vector, int apic_dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105cfe0)
Location: arch/x86/kernel/apic/x2apic_phys.c:45
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d4d0)
Location: arch/x86/kernel/apic/x2apic_cluster.c:37
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask
```
**Symbols:**

```
ffffffff8105cfe0-ffffffff8105d0a3: __x2apic_send_IPI_mask (STB_LOCAL)
ffffffff8105d4d0-ffffffff8105d5df: __x2apic_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask *mask, int vector, int apic_dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106d140)
Location: arch/x86/kernel/apic/x2apic_phys.c:45
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d580)
Location: arch/x86/kernel/apic/x2apic_cluster.c:37
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask
```
**Symbols:**

```
ffffffff8106d140-ffffffff8106d201: __x2apic_send_IPI_mask (STB_LOCAL)
ffffffff8106d580-ffffffff8106d6a3: __x2apic_send_IPI_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask *mask, int vector, int apic_dest);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106f3c0)
Location: arch/x86/kernel/apic/x2apic_phys.c:45
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106f800)
Location: arch/x86/kernel/apic/x2apic_cluster.c:37
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask
```
**Symbols:**

```
ffffffff8106f3c0-ffffffff8106f481: __x2apic_send_IPI_mask (STB_LOCAL)
ffffffff8106f800-ffffffff8106f923: __x2apic_send_IPI_mask (STB_LOCAL)
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
