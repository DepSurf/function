# Function: <code>enable_c02_store</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t enable_c02_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff810484e0)
Location: arch/x86/kernel/cpu/umwait.c:133
Inline: False
```
**Symbols:**

```
ffffffff810484e0-ffffffff81048585: enable_c02_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t enable_c02_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff81048db0)
Location: arch/x86/kernel/cpu/umwait.c:139
Inline: False
```
**Symbols:**

```
ffffffff81048db0-ffffffff81048e55: enable_c02_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t enable_c02_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff8104cd50)
Location: arch/x86/kernel/cpu/umwait.c:134
Inline: False
```
**Symbols:**

```
ffffffff8104cd50-ffffffff8104cdf4: enable_c02_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t enable_c02_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff8104c1b0)
Location: arch/x86/kernel/cpu/umwait.c:134
Inline: False
```
**Symbols:**

```
ffffffff8104c1b0-ffffffff8104c254: enable_c02_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t enable_c02_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff8104dcf0)
Location: arch/x86/kernel/cpu/umwait.c:134
Inline: False
```
**Symbols:**

```
ffffffff8104dcf0-ffffffff8104dd9d: enable_c02_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t enable_c02_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (0)
Location: arch/x86/kernel/cpu/umwait.c:134
Inline: False
```
**Symbols:**

```
ffffffff810554c0-ffffffff81055591: enable_c02_store (STB_LOCAL)
ffffffff81c9ad2d-ffffffff81c9ad7b: enable_c02_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t enable_c02_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (0)
Location: arch/x86/kernel/cpu/umwait.c:134
Inline: False
```
**Symbols:**

```
ffffffff81061420-ffffffff81061504: enable_c02_store (STB_LOCAL)
ffffffff81e4a24f-ffffffff81e4a29d: enable_c02_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t enable_c02_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (0)
Location: arch/x86/kernel/cpu/umwait.c:134
Inline: False
```
**Symbols:**

```
ffffffff8106fe00-ffffffff8106fee4: enable_c02_store (STB_LOCAL)
ffffffff820529d1-ffffffff82052a1f: enable_c02_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t enable_c02_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (0)
Location: arch/x86/kernel/cpu/umwait.c:134
Inline: False
```
**Symbols:**

```
ffffffff81071a10-ffffffff81071af4: enable_c02_store (STB_LOCAL)
ffffffff820d0e8f-ffffffff820d0edd: enable_c02_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t enable_c02_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (0)
Location: arch/x86/kernel/cpu/umwait.c:134
Inline: False
```
**Symbols:**

```
ffffffff81079230-ffffffff81079314: enable_c02_store (STB_LOCAL)
ffffffff821ab9ac-ffffffff821ab9fa: enable_c02_store.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
ssize_t enable_c02_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff81048f20)
Location: arch/x86/kernel/cpu/umwait.c:139
Inline: False
```
**Symbols:**

```
ffffffff81048f20-ffffffff81048fc5: enable_c02_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t enable_c02_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff81038210)
Location: arch/x86/kernel/cpu/umwait.c:139
Inline: False
```
**Symbols:**

```
ffffffff81038210-ffffffff810382b5: enable_c02_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t enable_c02_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff81048d60)
Location: arch/x86/kernel/cpu/umwait.c:139
Inline: False
```
**Symbols:**

```
ffffffff81048d60-ffffffff81048e05: enable_c02_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t enable_c02_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/umwait.c (ffffffff8104a170)
Location: arch/x86/kernel/cpu/umwait.c:139
Inline: False
```
**Symbols:**

```
ffffffff8104a170-ffffffff8104a215: enable_c02_store (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
