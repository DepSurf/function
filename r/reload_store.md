# Function: <code>reload_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t reload_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104c880)
Location: arch/x86/kernel/cpu/microcode/core.c:394
Inline: False
```
**Symbols:**

```
ffffffff8104c880-ffffffff8104c9d2: reload_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t reload_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104c900)
Location: arch/x86/kernel/cpu/microcode/core.c:386
Inline: False
```
**Symbols:**

```
ffffffff8104c900-ffffffff8104ca54: reload_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t reload_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104edf0)
Location: arch/x86/kernel/cpu/microcode/core.c:461
Inline: False
```
**Symbols:**

```
ffffffff8104edf0-ffffffff8104ef63: reload_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t reload_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104f0d0)
Location: arch/x86/kernel/cpu/microcode/core.c:501
Inline: True
```
**Symbols:**

```
ffffffff8104f0d0-ffffffff8104f236: reload_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t reload_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052b40)
Location: arch/x86/kernel/cpu/microcode/core.c:607
Inline: True
```
**Symbols:**

```
ffffffff81052b40-ffffffff81052c8a: reload_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t reload_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:613
Inline: True
```
**Symbols:**

```
ffffffff810556d0-ffffffff81055825: reload_store (STB_LOCAL)
ffffffff81055c8a-ffffffff81055ca7: reload_store.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t reload_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052e00)
Location: arch/x86/kernel/cpu/microcode/core.c:614
Inline: True
```
**Symbols:**

```
ffffffff81052d70-ffffffff81052ec5: reload_store (STB_LOCAL)
ffffffff8105332a-ffffffff81053347: reload_store.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t reload_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81055fae)
Location: arch/x86/kernel/cpu/microcode/core.c:613
Inline: True
```
**Symbols:**

```
ffffffff81055f20-ffffffff81056064: reload_store (STB_LOCAL)
ffffffff810564e9-ffffffff81056542: reload_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t reload_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810568ee)
Location: arch/x86/kernel/cpu/microcode/core.c:613
Inline: True
```
**Symbols:**

```
ffffffff81056860-ffffffff810569a4: reload_store (STB_LOCAL)
ffffffff81056db8-ffffffff81056e11: reload_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t reload_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:618
Inline: False
```
**Symbols:**

```
ffffffff8105b790-ffffffff8105b8d4: reload_store (STB_LOCAL)
ffffffff8105bf50-ffffffff8105bfa9: reload_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t reload_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:616
Inline: False
```
**Symbols:**

```
ffffffff8105a1e0-ffffffff8105a324: reload_store (STB_LOCAL)
ffffffff81bd5ec3-ffffffff81bd5f1c: reload_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t reload_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:616
Inline: False
```
**Symbols:**

```
ffffffff8105ab80-ffffffff8105acc9: reload_store (STB_LOCAL)
ffffffff81bc826f-ffffffff81bc82c8: reload_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t reload_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:616
Inline: False
```
**Symbols:**

```
ffffffff810640c0-ffffffff81064209: reload_store (STB_LOCAL)
ffffffff81c9c0ea-ffffffff81c9c143: reload_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t reload_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105646e)
Location: arch/x86/kernel/cpu/microcode/core.c:613
Inline: True
```
**Symbols:**

```
ffffffff810563e0-ffffffff81056524: reload_store (STB_LOCAL)
ffffffff81056938-ffffffff81056991: reload_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t reload_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104667e)
Location: arch/x86/kernel/cpu/microcode/core.c:613
Inline: True
```
**Symbols:**

```
ffffffff810465f0-ffffffff81046734: reload_store (STB_LOCAL)
ffffffff81046b48-ffffffff81046ba1: reload_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t reload_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105689e)
Location: arch/x86/kernel/cpu/microcode/core.c:613
Inline: True
```
**Symbols:**

```
ffffffff81056810-ffffffff81056954: reload_store (STB_LOCAL)
ffffffff81056d68-ffffffff81056dc1: reload_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t reload_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81057dee)
Location: arch/x86/kernel/cpu/microcode/core.c:613
Inline: True
```
**Symbols:**

```
ffffffff81057d60-ffffffff81057ea4: reload_store (STB_LOCAL)
ffffffff81058228-ffffffff81058281: reload_store.cold (STB_LOCAL)
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
