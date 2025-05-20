# Function: <code>show_trigger</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t show_trigger(struct device *s, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044570)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2187
Inline: False
```
**Symbols:**

```
ffffffff81044570-ffffffff810445e0: show_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t show_trigger(struct device *s, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044660)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2270
Inline: False
```
**Symbols:**

```
ffffffff81044660-ffffffff810446d8: show_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t show_trigger(struct device *s, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810461c0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2333
Inline: False
```
**Symbols:**

```
ffffffff810461c0-ffffffff81046238: show_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t show_trigger(struct device *s, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff8104bdf0)
Location: arch/x86/kernel/cpu/mcheck/dev-mcelog.c:116
Inline: False
```
**Symbols:**

```
ffffffff8104bdf0-ffffffff8104beea: show_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t show_trigger(struct device *s, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff8104f830)
Location: arch/x86/kernel/cpu/mcheck/dev-mcelog.c:97
Inline: False
```
**Symbols:**

```
ffffffff8104f830-ffffffff8104f92a: show_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
ssize_t show_trigger(struct device *s, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mcheck/dev-mcelog.c:97
Inline: False
```
**Symbols:**

```
ffffffff81052540-ffffffff81052633: show_trigger (STB_LOCAL)
ffffffff81052d25-ffffffff81052d3d: show_trigger.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
ssize_t show_trigger(struct device *s, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:92
Inline: False
```
**Symbols:**

```
ffffffff8104fba0-ffffffff8104fc93: show_trigger (STB_LOCAL)
ffffffff81050395-ffffffff810503ad: show_trigger.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t show_trigger(struct device *s, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:93
Inline: False
```
**Symbols:**

```
ffffffff81052cb0-ffffffff81052dac: show_trigger (STB_LOCAL)
ffffffff810534a5-ffffffff810534bd: show_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t show_trigger(struct device *s, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:93
Inline: False
```
**Symbols:**

```
ffffffff810535a0-ffffffff8105369c: show_trigger (STB_LOCAL)
ffffffff81053d95-ffffffff81053dad: show_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t show_trigger(struct device *s, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:94
Inline: False
```
**Symbols:**

```
ffffffff81058590-ffffffff8105868f: show_trigger (STB_LOCAL)
ffffffff81058db6-ffffffff81058dce: show_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t show_trigger(struct device *s, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:96
Inline: False
```
**Symbols:**

```
ffffffff81057390-ffffffff8105748f: show_trigger (STB_LOCAL)
ffffffff81bd5b31-ffffffff81bd5b49: show_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t show_trigger(struct device *s, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:96
Inline: False
```
**Symbols:**

```
ffffffff81057d00-ffffffff81057dfc: show_trigger (STB_LOCAL)
ffffffff81bc7ee3-ffffffff81bc7efb: show_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t show_trigger(struct device *s, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:96
Inline: False
```
**Symbols:**

```
ffffffff81060bd0-ffffffff81060ccc: show_trigger (STB_LOCAL)
ffffffff81c9bbd8-ffffffff81c9bbf0: show_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t show_trigger(struct device *s, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:96
Inline: False
```
**Symbols:**

```
ffffffff8106d450-ffffffff8106d55b: show_trigger (STB_LOCAL)
ffffffff81e4b004-ffffffff81e4b01c: show_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t show_trigger(struct device *s, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8107d630)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:96
Inline: False
```
**Symbols:**

```
ffffffff8107d630-ffffffff8107d762: show_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t show_trigger(struct device *s, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8107f940)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:96
Inline: False
```
**Symbols:**

```
ffffffff8107f940-ffffffff8107fa8a: show_trigger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t show_trigger(struct device *s, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81087450)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:96
Inline: False
```
**Symbols:**

```
ffffffff81087450-ffffffff8108759a: show_trigger (STB_LOCAL)
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
ssize_t show_trigger(struct device *s, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:93
Inline: False
```
**Symbols:**

```
ffffffff81053270-ffffffff8105336c: show_trigger (STB_LOCAL)
ffffffff81053915-ffffffff8105392d: show_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t show_trigger(struct device *s, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:93
Inline: False
```
**Symbols:**

```
ffffffff810431f0-ffffffff810432ec: show_trigger (STB_LOCAL)
ffffffff810439e5-ffffffff810439fd: show_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t show_trigger(struct device *s, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:93
Inline: False
```
**Symbols:**

```
ffffffff81053550-ffffffff8105364c: show_trigger (STB_LOCAL)
ffffffff81053d45-ffffffff81053d5d: show_trigger.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t show_trigger(struct device *s, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:93
Inline: False
```
**Symbols:**

```
ffffffff81054a10-ffffffff81054b0c: show_trigger (STB_LOCAL)
ffffffff810551c5-ffffffff810551dd: show_trigger.cold (STB_LOCAL)
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
