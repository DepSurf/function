# Function: <code>is_visible</code>

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
umode_t is_visible(struct kobject *kobj, struct attribute *attr, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005880)
Location: arch/x86/events/core.c:1690
Inline: False
```
**Symbols:**

```
ffffffff81005880-ffffffff810058b1: is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
umode_t is_visible(struct kobject *kobj, struct attribute *attr, int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006290)
Location: arch/x86/events/core.c:1763
Inline: True
```
**Symbols:**

```
ffffffff81006290-ffffffff810062ce: is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
umode_t is_visible(struct kobject *kobj, struct attribute *attr, int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810071b0)
Location: arch/x86/events/core.c:1764
Inline: True
```
**Symbols:**

```
ffffffff810071b0-ffffffff810071f4: is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
umode_t is_visible(struct kobject *kobj, struct attribute *attr, int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005ff0)
Location: arch/x86/events/core.c:1841
Inline: True
```
**Symbols:**

```
ffffffff81005ff0-ffffffff81006034: is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
umode_t is_visible(struct kobject *kobj, struct attribute *attr, int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005d60)
Location: arch/x86/events/core.c:1942
Inline: True
```
**Symbols:**

```
ffffffff81005d60-ffffffff81005da4: is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
umode_t is_visible(struct kobject *kobj, struct attribute *attr, int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006410)
Location: arch/x86/events/core.c:1940
Inline: True
```
**Symbols:**

```
ffffffff81006410-ffffffff81006454: is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
umode_t is_visible(struct kobject *kobj, struct attribute *attr, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005000)
Location: arch/x86/events/core.c:1952
Inline: False
```
**Symbols:**

```
ffffffff81005000-ffffffff81005062: is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
umode_t is_visible(struct kobject *kobj, struct attribute *attr, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005b00)
Location: arch/x86/events/core.c:1943
Inline: False
```
**Symbols:**

```
ffffffff81005b00-ffffffff81005b62: is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
umode_t is_visible(struct kobject *kobj, struct attribute *attr, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810052b0)
Location: arch/x86/events/core.c:1941
Inline: False
```
**Symbols:**

```
ffffffff810052b0-ffffffff81005312: is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
umode_t is_visible(struct kobject *kobj, struct attribute *attr, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100a9b0)
Location: arch/x86/events/core.c:1939
Inline: False
```
**Symbols:**

```
ffffffff8100a9b0-ffffffff8100aa12: is_visible (STB_LOCAL)
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
umode_t is_visible(struct kobject *kobj, struct attribute *attr, int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006290)
Location: arch/x86/events/core.c:1763
Inline: True
```
**Symbols:**

```
ffffffff81006290-ffffffff810062ce: is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
umode_t is_visible(struct kobject *kobj, struct attribute *attr, int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81004a10)
Location: arch/x86/events/core.c:1763
Inline: True
```
**Symbols:**

```
ffffffff81004a10-ffffffff81004a4e: is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
umode_t is_visible(struct kobject *kobj, struct attribute *attr, int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006250)
Location: arch/x86/events/core.c:1763
Inline: True
```
**Symbols:**

```
ffffffff81006250-ffffffff8100628e: is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
umode_t is_visible(struct kobject *kobj, struct attribute *attr, int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810063b0)
Location: arch/x86/events/core.c:1763
Inline: True
```
**Symbols:**

```
ffffffff810063b0-ffffffff810063ee: is_visible (STB_LOCAL)
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
