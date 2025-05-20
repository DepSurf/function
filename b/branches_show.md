# Function: <code>branches_show</code>

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
ssize_t branches_show(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100b130)
Location: arch/x86/events/intel/core.c:3813
Inline: False
```
**Symbols:**

```
ffffffff8100b130-ffffffff8100b157: branches_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t branches_show(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100b5d0)
Location: arch/x86/events/intel/core.c:3838
Inline: False
```
**Symbols:**

```
ffffffff8100b5d0-ffffffff8100b5f7: branches_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t branches_show(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100b700)
Location: arch/x86/events/intel/core.c:4115
Inline: False
```
**Symbols:**

```
ffffffff8100b700-ffffffff8100b727: branches_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t branches_show(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100bd40)
Location: arch/x86/events/intel/core.c:4368
Inline: False
```
**Symbols:**

```
ffffffff8100bd40-ffffffff8100bd67: branches_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t branches_show(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c150)
Location: arch/x86/events/intel/core.c:4386
Inline: False
```
**Symbols:**

```
ffffffff8100c150-ffffffff8100c177: branches_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t branches_show(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d300)
Location: arch/x86/events/intel/core.c:4424
Inline: False
```
**Symbols:**

```
ffffffff8100d300-ffffffff8100d327: branches_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t branches_show(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c2c0)
Location: arch/x86/events/intel/core.c:4800
Inline: False
```
**Symbols:**

```
ffffffff8100c2c0-ffffffff8100c2e7: branches_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t branches_show(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100cd30)
Location: arch/x86/events/intel/core.c:5090
Inline: False
```
**Symbols:**

```
ffffffff8100cd30-ffffffff8100cd57: branches_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t branches_show(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d270)
Location: arch/x86/events/intel/core.c:5110
Inline: False
```
**Symbols:**

```
ffffffff8100d270-ffffffff8100d297: branches_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t branches_show(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100a010)
Location: arch/x86/events/amd/core.c:1305
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100e390)
Location: arch/x86/events/intel/core.c:5180
Inline: False
```
**Symbols:**

```
ffffffff8100a010-ffffffff8100a043: branches_show (STB_LOCAL)
ffffffff8100e390-ffffffff8100e3c3: branches_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t branches_show(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100bb10)
Location: arch/x86/events/amd/core.c:1271
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff810118c0)
Location: arch/x86/events/intel/core.c:5306
Inline: False
```
**Symbols:**

```
ffffffff8100bb10-ffffffff8100bb43: branches_show (STB_LOCAL)
ffffffff810118c0-ffffffff810118f3: branches_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t branches_show(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100b410)
Location: arch/x86/events/amd/core.c:1268
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff81010f50)
Location: arch/x86/events/intel/core.c:5437
Inline: False
```
**Symbols:**

```
ffffffff8100b410-ffffffff8100b443: branches_show (STB_LOCAL)
ffffffff81010f50-ffffffff81010f83: branches_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t branches_show(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81010b90)
Location: arch/x86/events/amd/core.c:1278
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff810166a0)
Location: arch/x86/events/intel/core.c:5601
Inline: False
```
**Symbols:**

```
ffffffff81010b90-ffffffff81010bc3: branches_show (STB_LOCAL)
ffffffff810166a0-ffffffff810166d3: branches_show (STB_LOCAL)
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
ssize_t branches_show(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c150)
Location: arch/x86/events/intel/core.c:4386
Inline: False
```
**Symbols:**

```
ffffffff8100c150-ffffffff8100c177: branches_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t branches_show(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100a980)
Location: arch/x86/events/intel/core.c:4386
Inline: False
```
**Symbols:**

```
ffffffff8100a980-ffffffff8100a9a7: branches_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t branches_show(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c110)
Location: arch/x86/events/intel/core.c:4386
Inline: False
```
**Symbols:**

```
ffffffff8100c110-ffffffff8100c137: branches_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t branches_show(struct device *cdev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c340)
Location: arch/x86/events/intel/core.c:4386
Inline: False
```
**Symbols:**

```
ffffffff8100c340-ffffffff8100c367: branches_show (STB_LOCAL)
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
