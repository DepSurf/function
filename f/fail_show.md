# Function: <code>fail_show</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t fail_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811078f0)
Location: kernel/power/main.c:287
Inline: False
```
**Symbols:**

```
ffffffff811078f0-ffffffff81107912: fail_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t fail_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811123e0)
Location: kernel/power/main.c:319
Inline: False
```
**Symbols:**

```
ffffffff811123e0-ffffffff81112402: fail_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t fail_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8110f4b0)
Location: kernel/power/main.c:319
Inline: False
```
**Symbols:**

```
ffffffff8110f4b0-ffffffff8110f4d2: fail_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t fail_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8110ff50)
Location: kernel/power/main.c:319
Inline: False
```
**Symbols:**

```
ffffffff8110ff50-ffffffff8110ff72: fail_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t fail_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b7130)
Location: kernel/cpu.c:2373
Inline: False
```
```
In kernel/power/main.c (ffffffff8112f960)
Location: kernel/power/main.c:319
Inline: False
```
**Symbols:**

```
ffffffff810b7130-ffffffff810b718d: fail_show (STB_LOCAL)
ffffffff8112f960-ffffffff8112f982: fail_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t fail_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810cd8a0)
Location: kernel/cpu.c:2395
Inline: False
```
```
In kernel/power/main.c (ffffffff81151010)
Location: kernel/power/main.c:322
Inline: False
```
```
In drivers/regulator/core.c (ffffffff818e4d50)
Location: drivers/regulator/core.c:932
Inline: False
```
**Symbols:**

```
ffffffff810cd8a0-ffffffff810cd908: fail_show (STB_LOCAL)
ffffffff81151010-ffffffff8115103c: fail_show (STB_LOCAL)
ffffffff818e4d50-ffffffff818e4dc6: fail_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t fail_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810eb990)
Location: kernel/cpu.c:2421
Inline: False
```
```
In kernel/power/main.c (ffffffff8117fb40)
Location: kernel/power/main.c:326
Inline: False
```
```
In drivers/regulator/core.c (ffffffff81a39990)
Location: drivers/regulator/core.c:932
Inline: False
```
**Symbols:**

```
ffffffff810eb990-ffffffff810eb9f8: fail_show (STB_LOCAL)
ffffffff8117fb40-ffffffff8117fb6c: fail_show (STB_LOCAL)
ffffffff81a39990-ffffffff81a39a06: fail_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t fail_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f7670)
Location: kernel/cpu.c:2806
Inline: False
```
```
In kernel/power/main.c (ffffffff81190910)
Location: kernel/power/main.c:367
Inline: False
```
```
In drivers/regulator/core.c (ffffffff81a83570)
Location: drivers/regulator/core.c:998
Inline: False
```
**Symbols:**

```
ffffffff810f7670-ffffffff810f76d8: fail_show (STB_LOCAL)
ffffffff81190910-ffffffff8119093c: fail_show (STB_LOCAL)
ffffffff81a83570-ffffffff81a835e6: fail_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t fail_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81100a20)
Location: kernel/cpu.c:2860
Inline: False
```
```
In kernel/power/main.c (ffffffff8119f2d0)
Location: kernel/power/main.c:351
Inline: False
```
```
In drivers/regulator/core.c (ffffffff81ad5d20)
Location: drivers/regulator/core.c:1000
Inline: False
```
**Symbols:**

```
ffffffff81100a20-ffffffff81100a88: fail_show (STB_LOCAL)
ffffffff8119f2d0-ffffffff8119f2fc: fail_show (STB_LOCAL)
ffffffff81ad5d20-ffffffff81ad5d96: fail_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
ssize_t fail_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffff80001016e9d8)
Location: kernel/power/main.c:287
Inline: False
```
**Symbols:**

```
ffff80001016e9d8-ffff80001016ea18: fail_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t fail_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (c03b96c8)
Location: kernel/power/main.c:287
Inline: False
```
**Symbols:**

```
c03b96c8-c03b96fc: fail_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t fail_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (c0000000001c6480)
Location: kernel/power/main.c:287
Inline: False
```
**Symbols:**

```
c0000000001c6480-c0000000001c64cc: fail_show (STB_LOCAL)
```
</details>
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
ssize_t fail_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81100c00)
Location: kernel/power/main.c:287
Inline: False
```
**Symbols:**

```
ffffffff81100c00-ffffffff81100c22: fail_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t fail_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810f0df0)
Location: kernel/power/main.c:287
Inline: False
```
**Symbols:**

```
ffffffff810f0df0-ffffffff810f0e12: fail_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t fail_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810fddc0)
Location: kernel/power/main.c:287
Inline: False
```
**Symbols:**

```
ffffffff810fddc0-ffffffff810fdde2: fail_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t fail_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81109080)
Location: kernel/power/main.c:287
Inline: False
```
**Symbols:**

```
ffffffff81109080-ffffffff811090a2: fail_show (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kobject *kobj</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct kobj_attribute *attr</code> ➡️ <code>struct device_attribute *attr</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
