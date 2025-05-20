# Function: <code>lbr_is_visible</code>

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
umode_t lbr_is_visible(struct kobject *kobj, struct attribute *attr, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100b940)
Location: arch/x86/events/intel/core.c:4421
Inline: False
```
**Symbols:**

```
ffffffff8100b940-ffffffff8100b95d: lbr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
umode_t lbr_is_visible(struct kobject *kobj, struct attribute *attr, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100bd50)
Location: arch/x86/events/intel/core.c:4439
Inline: False
```
**Symbols:**

```
ffffffff8100bd50-ffffffff8100bd6d: lbr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
umode_t lbr_is_visible(struct kobject *kobj, struct attribute *attr, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d140)
Location: arch/x86/events/intel/core.c:4477
Inline: False
```
**Symbols:**

```
ffffffff8100d140-ffffffff8100d15d: lbr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
umode_t lbr_is_visible(struct kobject *kobj, struct attribute *attr, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c100)
Location: arch/x86/events/intel/core.c:4853
Inline: False
```
**Symbols:**

```
ffffffff8100c100-ffffffff8100c11d: lbr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
umode_t lbr_is_visible(struct kobject *kobj, struct attribute *attr, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c850)
Location: arch/x86/events/intel/core.c:5143
Inline: False
```
**Symbols:**

```
ffffffff8100c850-ffffffff8100c86d: lbr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
umode_t lbr_is_visible(struct kobject *kobj, struct attribute *attr, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100cd30)
Location: arch/x86/events/intel/core.c:5163
Inline: False
```
**Symbols:**

```
ffffffff8100cd30-ffffffff8100cd4d: lbr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
umode_t lbr_is_visible(struct kobject *kobj, struct attribute *attr, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100dcf0)
Location: arch/x86/events/intel/core.c:5233
Inline: False
```
**Symbols:**

```
ffffffff8100dcf0-ffffffff8100dd19: lbr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
umode_t lbr_is_visible(struct kobject *kobj, struct attribute *attr, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81010f20)
Location: arch/x86/events/intel/core.c:5359
Inline: False
```
**Symbols:**

```
ffffffff81010f20-ffffffff81010f49: lbr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
umode_t lbr_is_visible(struct kobject *kobj, struct attribute *attr, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81010a20)
Location: arch/x86/events/intel/core.c:5499
Inline: False
```
**Symbols:**

```
ffffffff81010a20-ffffffff81010a49: lbr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
umode_t lbr_is_visible(struct kobject *kobj, struct attribute *attr, int i);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81017320)
Location: arch/x86/events/intel/core.c:5636
Inline: True
```
**Symbols:**

```
ffffffff81017320-ffffffff81017362: lbr_is_visible (STB_LOCAL)
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
umode_t lbr_is_visible(struct kobject *kobj, struct attribute *attr, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100bd50)
Location: arch/x86/events/intel/core.c:4439
Inline: False
```
**Symbols:**

```
ffffffff8100bd50-ffffffff8100bd6d: lbr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
umode_t lbr_is_visible(struct kobject *kobj, struct attribute *attr, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100a6d0)
Location: arch/x86/events/intel/core.c:4439
Inline: False
```
**Symbols:**

```
ffffffff8100a6d0-ffffffff8100a6ed: lbr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
umode_t lbr_is_visible(struct kobject *kobj, struct attribute *attr, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100bd10)
Location: arch/x86/events/intel/core.c:4439
Inline: False
```
**Symbols:**

```
ffffffff8100bd10-ffffffff8100bd2d: lbr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
umode_t lbr_is_visible(struct kobject *kobj, struct attribute *attr, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100bef0)
Location: arch/x86/events/intel/core.c:4439
Inline: False
```
**Symbols:**

```
ffffffff8100bef0-ffffffff8100bf0d: lbr_is_visible (STB_LOCAL)
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
