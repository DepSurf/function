# Function: <code>set_sysctl_tfa</code>

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
ssize_t set_sysctl_tfa(struct device *cdev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100bda0)
Location: arch/x86/events/intel/core.c:4341
Inline: False
```
**Symbols:**

```
ffffffff8100bda0-ffffffff8100be28: set_sysctl_tfa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t set_sysctl_tfa(struct device *cdev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c1b0)
Location: arch/x86/events/intel/core.c:4359
Inline: False
```
**Symbols:**

```
ffffffff8100c1b0-ffffffff8100c238: set_sysctl_tfa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t set_sysctl_tfa(struct device *cdev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d360)
Location: arch/x86/events/intel/core.c:4397
Inline: False
```
**Symbols:**

```
ffffffff8100d360-ffffffff8100d3e8: set_sysctl_tfa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t set_sysctl_tfa(struct device *cdev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c3c0)
Location: arch/x86/events/intel/core.c:4773
Inline: False
```
**Symbols:**

```
ffffffff8100c3c0-ffffffff8100c448: set_sysctl_tfa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t set_sysctl_tfa(struct device *cdev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100cdc0)
Location: arch/x86/events/intel/core.c:5063
Inline: False
```
**Symbols:**

```
ffffffff8100cdc0-ffffffff8100ce51: set_sysctl_tfa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t set_sysctl_tfa(struct device *cdev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:5083
Inline: False
```
**Symbols:**

```
ffffffff8100d890-ffffffff8100d95b: set_sysctl_tfa (STB_LOCAL)
ffffffff81c957b2-ffffffff81c957f0: set_sysctl_tfa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t set_sysctl_tfa(struct device *cdev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:5153
Inline: False
```
**Symbols:**

```
ffffffff8100ec30-ffffffff8100ed03: set_sysctl_tfa (STB_LOCAL)
ffffffff81e44c6e-ffffffff81e44cab: set_sysctl_tfa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t set_sysctl_tfa(struct device *cdev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:5279
Inline: False
```
**Symbols:**

```
ffffffff81012360-ffffffff81012433: set_sysctl_tfa (STB_LOCAL)
ffffffff82050634-ffffffff82050671: set_sysctl_tfa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t set_sysctl_tfa(struct device *cdev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:5410
Inline: False
```
**Symbols:**

```
ffffffff81011860-ffffffff81011942: set_sysctl_tfa (STB_LOCAL)
ffffffff820cea6e-ffffffff820ceaad: set_sysctl_tfa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t set_sysctl_tfa(struct device *cdev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:5574
Inline: False
```
**Symbols:**

```
ffffffff81017000-ffffffff810170e2: set_sysctl_tfa (STB_LOCAL)
ffffffff821a92c9-ffffffff821a9308: set_sysctl_tfa.cold (STB_LOCAL)
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
ssize_t set_sysctl_tfa(struct device *cdev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c1b0)
Location: arch/x86/events/intel/core.c:4359
Inline: False
```
**Symbols:**

```
ffffffff8100c1b0-ffffffff8100c238: set_sysctl_tfa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t set_sysctl_tfa(struct device *cdev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100a9e0)
Location: arch/x86/events/intel/core.c:4359
Inline: False
```
**Symbols:**

```
ffffffff8100a9e0-ffffffff8100aa68: set_sysctl_tfa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t set_sysctl_tfa(struct device *cdev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c170)
Location: arch/x86/events/intel/core.c:4359
Inline: False
```
**Symbols:**

```
ffffffff8100c170-ffffffff8100c1f8: set_sysctl_tfa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t set_sysctl_tfa(struct device *cdev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c3a0)
Location: arch/x86/events/intel/core.c:4359
Inline: False
```
**Symbols:**

```
ffffffff8100c3a0-ffffffff8100c428: set_sysctl_tfa (STB_LOCAL)
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
