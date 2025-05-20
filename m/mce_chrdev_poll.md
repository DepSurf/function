# Function: <code>mce_chrdev_poll</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int mce_chrdev_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044d20)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1900
Inline: True
```
**Symbols:**

```
ffffffff81044d20-ffffffff81044d6c: mce_chrdev_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int mce_chrdev_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044d70)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1979
Inline: True
```
**Symbols:**

```
ffffffff81044d70-ffffffff81044dbc: mce_chrdev_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned int mce_chrdev_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810469f0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2042
Inline: True
```
**Symbols:**

```
ffffffff810469f0-ffffffff81046a3c: mce_chrdev_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int mce_chrdev_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff8104c590)
Location: arch/x86/kernel/cpu/mcheck/dev-mcelog.c:313
Inline: True
```
**Symbols:**

```
ffffffff8104c590-ffffffff8104c5df: mce_chrdev_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int mce_chrdev_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff8104fe30)
Location: arch/x86/kernel/cpu/mcheck/dev-mcelog.c:246
Inline: True
```
**Symbols:**

```
ffffffff8104fe30-ffffffff8104fe82: mce_chrdev_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
__poll_t mce_chrdev_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff81052aa0)
Location: arch/x86/kernel/cpu/mcheck/dev-mcelog.c:246
Inline: True
```
**Symbols:**

```
ffffffff81052aa0-ffffffff81052aed: mce_chrdev_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
__poll_t mce_chrdev_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81050100)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:241
Inline: True
```
**Symbols:**

```
ffffffff81050100-ffffffff81050152: mce_chrdev_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
__poll_t mce_chrdev_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81053200)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:242
Inline: True
```
**Symbols:**

```
ffffffff81053200-ffffffff8105325a: mce_chrdev_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
__poll_t mce_chrdev_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81053af0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:242
Inline: True
```
**Symbols:**

```
ffffffff81053af0-ffffffff81053b4a: mce_chrdev_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
__poll_t mce_chrdev_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81058ae0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:243
Inline: True
```
**Symbols:**

```
ffffffff81058ae0-ffffffff81058b42: mce_chrdev_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
__poll_t mce_chrdev_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff810578f0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:245
Inline: True
```
**Symbols:**

```
ffffffff810578f0-ffffffff81057952: mce_chrdev_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
__poll_t mce_chrdev_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81058250)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:245
Inline: True
```
**Symbols:**

```
ffffffff81058250-ffffffff810582b2: mce_chrdev_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
__poll_t mce_chrdev_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81061120)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:245
Inline: True
```
**Symbols:**

```
ffffffff81061120-ffffffff81061182: mce_chrdev_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__poll_t mce_chrdev_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8106dad0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:245
Inline: False
```
**Symbols:**

```
ffffffff8106dad0-ffffffff8106db40: mce_chrdev_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__poll_t mce_chrdev_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8107dd60)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:245
Inline: False
```
**Symbols:**

```
ffffffff8107dd60-ffffffff8107ddd0: mce_chrdev_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__poll_t mce_chrdev_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81080140)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:244
Inline: False
```
**Symbols:**

```
ffffffff81080140-ffffffff810801b0: mce_chrdev_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__poll_t mce_chrdev_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81087c50)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:244
Inline: False
```
**Symbols:**

```
ffffffff81087c50-ffffffff81087cc0: mce_chrdev_poll (STB_LOCAL)
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
__poll_t mce_chrdev_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81053170)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:242
Inline: False
```
**Symbols:**

```
ffffffff81053170-ffffffff810531b8: mce_chrdev_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
__poll_t mce_chrdev_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81043740)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:242
Inline: True
```
**Symbols:**

```
ffffffff81043740-ffffffff8104379a: mce_chrdev_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
__poll_t mce_chrdev_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81053aa0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:242
Inline: True
```
**Symbols:**

```
ffffffff81053aa0-ffffffff81053afa: mce_chrdev_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
__poll_t mce_chrdev_poll(struct file *file, poll_table *wait);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81054ff0)
Location: arch/x86/kernel/cpu/mce/dev-mcelog.c:242
Inline: True
```
**Symbols:**

```
ffffffff81054ff0-ffffffff8105504a: mce_chrdev_poll (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned int</code> ➡️ <code>__poll_t</code>
</li>
</ul>
</details>
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
