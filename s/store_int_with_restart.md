# Function: <code>store_int_with_restart</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t store_int_with_restart(struct device *s, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810444b0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2256
Inline: False
```
**Symbols:**

```
ffffffff810444b0-ffffffff810444e0: store_int_with_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t store_int_with_restart(struct device *s, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810445a0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2339
Inline: False
```
**Symbols:**

```
ffffffff810445a0-ffffffff810445d0: store_int_with_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t store_int_with_restart(struct device *s, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046100)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2402
Inline: False
```
**Symbols:**

```
ffffffff81046100-ffffffff81046130: store_int_with_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t store_int_with_restart(struct device *s, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045df0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2112
Inline: False
```
**Symbols:**

```
ffffffff81045df0-ffffffff81045e20: store_int_with_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t store_int_with_restart(struct device *s, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81049df0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2130
Inline: True
```
**Symbols:**

```
ffffffff81049df0-ffffffff81049e61: store_int_with_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t store_int_with_restart(struct device *s, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104c440)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2126
Inline: True
```
**Symbols:**

```
ffffffff8104c440-ffffffff8104c49c: store_int_with_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t store_int_with_restart(struct device *s, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81049b30)
Location: arch/x86/kernel/cpu/mce/core.c:2149
Inline: True
```
**Symbols:**

```
ffffffff81049b30-ffffffff81049b8c: store_int_with_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
ssize_t store_int_with_restart(struct device *s, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ca70)
Location: arch/x86/kernel/cpu/mce/core.c:2204
Inline: True
```
**Symbols:**

```
ffffffff8104ca70-ffffffff8104cacc: store_int_with_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t store_int_with_restart(struct device *s, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d430)
Location: arch/x86/kernel/cpu/mce/core.c:2204
Inline: True
```
**Symbols:**

```
ffffffff8104d430-ffffffff8104d48c: store_int_with_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t store_int_with_restart(struct device *s, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810526f0)
Location: arch/x86/kernel/cpu/mce/core.c:2330
Inline: True
```
**Symbols:**

```
ffffffff810526f0-ffffffff81052787: store_int_with_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ssize_t store_int_with_restart(struct device *s, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810518d0)
Location: arch/x86/kernel/cpu/mce/core.c:2406
Inline: True
```
**Symbols:**

```
ffffffff810518d0-ffffffff81051967: store_int_with_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t store_int_with_restart(struct device *s, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810530a0)
Location: arch/x86/kernel/cpu/mce/core.c:2417
Inline: True
```
**Symbols:**

```
ffffffff810530a0-ffffffff81053140: store_int_with_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t store_int_with_restart(struct device *s, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105b740)
Location: arch/x86/kernel/cpu/mce/core.c:2480
Inline: True
```
**Symbols:**

```
ffffffff8105b740-ffffffff8105b7fe: store_int_with_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ssize_t store_int_with_restart(struct device *s, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81067ed0)
Location: arch/x86/kernel/cpu/mce/core.c:2494
Inline: True
```
**Symbols:**

```
ffffffff81067ed0-ffffffff81067f9a: store_int_with_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t store_int_with_restart(struct device *s, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81077480)
Location: arch/x86/kernel/cpu/mce/core.c:2494
Inline: True
```
**Symbols:**

```
ffffffff81077480-ffffffff810774f4: store_int_with_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t store_int_with_restart(struct device *s, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81079530)
Location: arch/x86/kernel/cpu/mce/core.c:2511
Inline: True
```
**Symbols:**

```
ffffffff81079530-ffffffff810795c7: store_int_with_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t store_int_with_restart(struct device *s, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81080db0)
Location: arch/x86/kernel/cpu/mce/core.c:2540
Inline: True
```
**Symbols:**

```
ffffffff81080db0-ffffffff81080e47: store_int_with_restart (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
ssize_t store_int_with_restart(struct device *s, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d5a0)
Location: arch/x86/kernel/cpu/mce/core.c:2204
Inline: True
```
**Symbols:**

```
ffffffff8104d5a0-ffffffff8104d5fc: store_int_with_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ssize_t store_int_with_restart(struct device *s, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103cc00)
Location: arch/x86/kernel/cpu/mce/core.c:2204
Inline: True
```
**Symbols:**

```
ffffffff8103cc00-ffffffff8103cc5c: store_int_with_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ssize_t store_int_with_restart(struct device *s, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d3e0)
Location: arch/x86/kernel/cpu/mce/core.c:2204
Inline: True
```
**Symbols:**

```
ffffffff8104d3e0-ffffffff8104d43c: store_int_with_restart (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ssize_t store_int_with_restart(struct device *s, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e810)
Location: arch/x86/kernel/cpu/mce/core.c:2204
Inline: True
```
**Symbols:**

```
ffffffff8104e810-ffffffff8104e86c: store_int_with_restart (STB_LOCAL)
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
