# Function: <code>devm_mbox_controller_unregister</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void devm_mbox_controller_unregister(struct device *dev, struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff8187a240)
Location: drivers/mailbox/mailbox.c:612
Inline: True
```
**Symbols:**

```
ffffffff8187a240-ffffffff8187a269: devm_mbox_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void devm_mbox_controller_unregister(struct device *dev, struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff818bf8b3)
Location: drivers/mailbox/mailbox.c:611
Inline: True
```
**Symbols:**

```
ffffffff818bf8b3-ffffffff818bf8c6: devm_mbox_controller_unregister.cold (STB_LOCAL)
ffffffff818bf7f0-ffffffff818bf819: devm_mbox_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void devm_mbox_controller_unregister(struct device *dev, struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff818f2340)
Location: drivers/mailbox/mailbox.c:611
Inline: True
```
**Symbols:**

```
ffffffff818f2340-ffffffff818f2369: devm_mbox_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void devm_mbox_controller_unregister(struct device *dev, struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff819c7ab0)
Location: drivers/mailbox/mailbox.c:611
Inline: True
```
**Symbols:**

```
ffffffff819c7ab0-ffffffff819c7ad9: devm_mbox_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void devm_mbox_controller_unregister(struct device *dev, struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff819c7a00)
Location: drivers/mailbox/mailbox.c:613
Inline: True
```
**Symbols:**

```
ffffffff819c7a00-ffffffff819c7a29: devm_mbox_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void devm_mbox_controller_unregister(struct device *dev, struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff819ac940)
Location: drivers/mailbox/mailbox.c:613
Inline: True
```
**Symbols:**

```
ffffffff819ac940-ffffffff819ac969: devm_mbox_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devm_mbox_controller_unregister(struct device *dev, struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81a5a870)
Location: drivers/mailbox/mailbox.c:613
Inline: False
```
**Symbols:**

```
ffffffff81a5a870-ffffffff81a5a899: devm_mbox_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devm_mbox_controller_unregister(struct device *dev, struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81bc9fe0)
Location: drivers/mailbox/mailbox.c:620
Inline: False
```
**Symbols:**

```
ffffffff81bc9fe0-ffffffff81bca025: devm_mbox_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devm_mbox_controller_unregister(struct device *dev, struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81d73570)
Location: drivers/mailbox/mailbox.c:620
Inline: False
```
**Symbols:**

```
ffffffff81d73570-ffffffff81d735b5: devm_mbox_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devm_mbox_controller_unregister(struct device *dev, struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81de1340)
Location: drivers/mailbox/mailbox.c:660
Inline: False
```
**Symbols:**

```
ffffffff81de1340-ffffffff81de1385: devm_mbox_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devm_mbox_controller_unregister(struct device *dev, struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81e97300)
Location: drivers/mailbox/mailbox.c:661
Inline: False
```
**Symbols:**

```
ffffffff81e97300-ffffffff81e97345: devm_mbox_controller_unregister (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void devm_mbox_controller_unregister(struct device *dev, struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffff800010b79ee0)
Location: drivers/mailbox/mailbox.c:611
Inline: True
```
**Symbols:**

```
ffff800010b79ee0-ffff800010b79f38: devm_mbox_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void devm_mbox_controller_unregister(struct device *dev, struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (c0c601ec)
Location: drivers/mailbox/mailbox.c:611
Inline: True
```
**Symbols:**

```
c0c601ec-c0c6023c: devm_mbox_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devm_mbox_controller_unregister(struct device *dev, struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (c000000000c58f60)
Location: drivers/mailbox/mailbox.c:611
Inline: False
```
**Symbols:**

```
c000000000c58f60-c000000000c58fb8: devm_mbox_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void devm_mbox_controller_unregister(struct device *dev, struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffe00072c578)
Location: drivers/mailbox/mailbox.c:611
Inline: True
```
**Symbols:**

```
ffffffe00072c578-ffffffe00072c5ca: devm_mbox_controller_unregister (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void devm_mbox_controller_unregister(struct device *dev, struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81893670)
Location: drivers/mailbox/mailbox.c:611
Inline: True
```
**Symbols:**

```
ffffffff81893670-ffffffff81893699: devm_mbox_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void devm_mbox_controller_unregister(struct device *dev, struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff8184bb70)
Location: drivers/mailbox/mailbox.c:611
Inline: True
```
**Symbols:**

```
ffffffff8184bb70-ffffffff8184bb99: devm_mbox_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void devm_mbox_controller_unregister(struct device *dev, struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff818e7170)
Location: drivers/mailbox/mailbox.c:611
Inline: True
```
**Symbols:**

```
ffffffff818e7170-ffffffff818e7199: devm_mbox_controller_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void devm_mbox_controller_unregister(struct device *dev, struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81903df0)
Location: drivers/mailbox/mailbox.c:611
Inline: True
```
**Symbols:**

```
ffffffff81903df0-ffffffff81903e19: devm_mbox_controller_unregister (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
