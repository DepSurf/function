# Function: <code>show_sysctl_tfa</code>

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
ssize_t show_sysctl_tfa(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100bd10)
Location: arch/x86/events/intel/core.c:4334
Inline: False
```
**Symbols:**

```
ffffffff8100bd10-ffffffff8100bd3b: show_sysctl_tfa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t show_sysctl_tfa(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c120)
Location: arch/x86/events/intel/core.c:4352
Inline: False
```
**Symbols:**

```
ffffffff8100c120-ffffffff8100c14b: show_sysctl_tfa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t show_sysctl_tfa(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d2d0)
Location: arch/x86/events/intel/core.c:4390
Inline: False
```
**Symbols:**

```
ffffffff8100d2d0-ffffffff8100d2fb: show_sysctl_tfa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t show_sysctl_tfa(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c290)
Location: arch/x86/events/intel/core.c:4766
Inline: False
```
**Symbols:**

```
ffffffff8100c290-ffffffff8100c2bb: show_sysctl_tfa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t show_sysctl_tfa(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100cd00)
Location: arch/x86/events/intel/core.c:5056
Inline: False
```
**Symbols:**

```
ffffffff8100cd00-ffffffff8100cd2b: show_sysctl_tfa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t show_sysctl_tfa(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:5076
Inline: False
```
**Symbols:**

```
ffffffff8100d840-ffffffff8100d884: show_sysctl_tfa (STB_LOCAL)
ffffffff81c95797-ffffffff81c957b2: show_sysctl_tfa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t show_sysctl_tfa(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:5146
Inline: False
```
**Symbols:**

```
ffffffff8100ebe0-ffffffff8100ec2f: show_sysctl_tfa (STB_LOCAL)
ffffffff81e44c53-ffffffff81e44c6e: show_sysctl_tfa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t show_sysctl_tfa(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:5272
Inline: False
```
**Symbols:**

```
ffffffff81012300-ffffffff8101234f: show_sysctl_tfa (STB_LOCAL)
ffffffff82050619-ffffffff82050634: show_sysctl_tfa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t show_sysctl_tfa(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:5403
Inline: False
```
**Symbols:**

```
ffffffff81011800-ffffffff8101184f: show_sysctl_tfa (STB_LOCAL)
ffffffff820cea53-ffffffff820cea6e: show_sysctl_tfa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t show_sysctl_tfa(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:5567
Inline: False
```
**Symbols:**

```
ffffffff81016fa0-ffffffff81016fef: show_sysctl_tfa (STB_LOCAL)
ffffffff821a92ae-ffffffff821a92c9: show_sysctl_tfa.cold (STB_LOCAL)
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
ssize_t show_sysctl_tfa(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c120)
Location: arch/x86/events/intel/core.c:4352
Inline: False
```
**Symbols:**

```
ffffffff8100c120-ffffffff8100c14b: show_sysctl_tfa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t show_sysctl_tfa(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100a950)
Location: arch/x86/events/intel/core.c:4352
Inline: False
```
**Symbols:**

```
ffffffff8100a950-ffffffff8100a97b: show_sysctl_tfa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t show_sysctl_tfa(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c0e0)
Location: arch/x86/events/intel/core.c:4352
Inline: False
```
**Symbols:**

```
ffffffff8100c0e0-ffffffff8100c10b: show_sysctl_tfa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t show_sysctl_tfa(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c310)
Location: arch/x86/events/intel/core.c:4352
Inline: False
```
**Symbols:**

```
ffffffff8100c310-ffffffff8100c33b: show_sysctl_tfa (STB_LOCAL)
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
