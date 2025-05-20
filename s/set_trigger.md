# Function: <code>set_trigger</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t set_trigger(struct device *s, struct device_attribute *attr, const char *buf, size_t siz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810444e0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2194
Inline: False
```
**Symbols:**

```
ffffffff810444e0-ffffffff8104456c: set_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t set_trigger(struct device *s, struct device_attribute *attr, const char *buf, size_t siz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810445d0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2277
Inline: False
```
**Symbols:**

```
ffffffff810445d0-ffffffff8104465f: set_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t set_trigger(struct device *s, struct device_attribute *attr, const char *buf, size_t siz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046130)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2340
Inline: False
```
**Symbols:**

```
ffffffff81046130-ffffffff810461bf: set_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t set_trigger(struct device *s, struct device_attribute *attr, const char *buf, size_t siz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff8104bd60)
Location: arch/x86/kernel/cpu/mcheck/dev-mcelog.c:123
Inline: False
```
**Symbols:**

```
ffffffff8104bd60-ffffffff8104bde2: set_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t set_trigger(struct device *s, struct device_attribute *attr, const char *buf, size_t siz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff8104f7a0)
Location: arch/x86/kernel/cpu/mcheck/dev-mcelog.c:104
Inline: False
```
**Symbols:**

```
ffffffff8104f7a0-ffffffff8104f822: set_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
ssize_t set_trigger(struct device *s, struct device_attribute *attr, const char *buf, size_t siz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mcheck/dev-mcelog.c:104
Inline: False
```
**Symbols:**

```
ffffffff810524c0-ffffffff81052532: set_trigger (STB_LOCAL)
ffffffff81052d0d-ffffffff81052d25: set_trigger.cold.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
ssize_t set_trigger(struct device *s, struct device_attribute *attr, const char *buf, size_t siz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:99
Inline: False
```
**Symbols:**

```
ffffffff8104fb20-ffffffff8104fb92: set_trigger (STB_LOCAL)
ffffffff8105037d-ffffffff81050395: set_trigger.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t set_trigger(struct device *s, struct device_attribute *attr, const char *buf, size_t siz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:100
Inline: False
```
**Symbols:**

```
ffffffff81052c30-ffffffff81052ca2: set_trigger (STB_LOCAL)
ffffffff8105348d-ffffffff810534a5: set_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t set_trigger(struct device *s, struct device_attribute *attr, const char *buf, size_t siz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:100
Inline: False
```
**Symbols:**

```
ffffffff81053520-ffffffff81053592: set_trigger (STB_LOCAL)
ffffffff81053d7d-ffffffff81053d95: set_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t set_trigger(struct device *s, struct device_attribute *attr, const char *buf, size_t siz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:101
Inline: False
```
**Symbols:**

```
ffffffff81058510-ffffffff81058583: set_trigger (STB_LOCAL)
ffffffff81058d9e-ffffffff81058db6: set_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t set_trigger(struct device *s, struct device_attribute *attr, const char *buf, size_t siz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:103
Inline: False
```
**Symbols:**

```
ffffffff81057310-ffffffff81057383: set_trigger (STB_LOCAL)
ffffffff81bd5b19-ffffffff81bd5b31: set_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t set_trigger(struct device *s, struct device_attribute *attr, const char *buf, size_t siz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:103
Inline: False
```
**Symbols:**

```
ffffffff81057c80-ffffffff81057cf3: set_trigger (STB_LOCAL)
ffffffff81bc7ecb-ffffffff81bc7ee3: set_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t set_trigger(struct device *s, struct device_attribute *attr, const char *buf, size_t siz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:103
Inline: False
```
**Symbols:**

```
ffffffff81060b50-ffffffff81060bc3: set_trigger (STB_LOCAL)
ffffffff81c9bbc0-ffffffff81c9bbd8: set_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t set_trigger(struct device *s, struct device_attribute *attr, const char *buf, size_t siz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:103
Inline: False
```
**Symbols:**

```
ffffffff8106d3d0-ffffffff8106d44c: set_trigger (STB_LOCAL)
ffffffff81e4afec-ffffffff81e4b004: set_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t set_trigger(struct device *s, struct device_attribute *attr, const char *buf, size_t siz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8107d590)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:103
Inline: False
```
**Symbols:**

```
ffffffff8107d590-ffffffff8107d61c: set_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t set_trigger(struct device *s, struct device_attribute *attr, const char *buf, size_t siz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8107faa0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:103
Inline: False
```
**Symbols:**

```
ffffffff8107faa0-ffffffff8107fb5a: set_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t set_trigger(struct device *s, struct device_attribute *attr, const char *buf, size_t siz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff810875b0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:103
Inline: False
```
**Symbols:**

```
ffffffff810875b0-ffffffff8108766a: set_trigger (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t set_trigger(struct device *s, struct device_attribute *attr, const char *buf, size_t siz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:100
Inline: False
```
**Symbols:**

```
ffffffff810531f0-ffffffff81053262: set_trigger (STB_LOCAL)
ffffffff810538fd-ffffffff81053915: set_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t set_trigger(struct device *s, struct device_attribute *attr, const char *buf, size_t siz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:100
Inline: False
```
**Symbols:**

```
ffffffff81043170-ffffffff810431e2: set_trigger (STB_LOCAL)
ffffffff810439cd-ffffffff810439e5: set_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t set_trigger(struct device *s, struct device_attribute *attr, const char *buf, size_t siz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:100
Inline: False
```
**Symbols:**

```
ffffffff810534d0-ffffffff81053542: set_trigger (STB_LOCAL)
ffffffff81053d2d-ffffffff81053d45: set_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t set_trigger(struct device *s, struct device_attribute *attr, const char *buf, size_t siz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:100
Inline: False
```
**Symbols:**

```
ffffffff81054990-ffffffff81054a02: set_trigger (STB_LOCAL)
ffffffff810551ad-ffffffff810551c5: set_trigger.cold (STB_LOCAL)
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
