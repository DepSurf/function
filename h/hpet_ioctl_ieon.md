# Function: <code>hpet_ioctl_ieon</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff815198d3)
Location: drivers/char/hpet.c:455
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff8156c5d3)
Location: drivers/char/hpet.c:455
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff81598d43)
Location: drivers/char/hpet.c:455
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff815acacd)
Location: drivers/char/hpet.c:456
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff8161349d)
Location: drivers/char/hpet.c:456
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff8164d4bd)
Location: drivers/char/hpet.c:456
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff8166b3dd)
Location: drivers/char/hpet.c:456
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff816a0f87)
Location: drivers/char/hpet.c:453
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff816c3d27)
Location: drivers/char/hpet.c:453
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int hpet_ioctl_ieon(struct hpet_dev *devp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (0)
Location: drivers/char/hpet.c:453
Inline: False
```
**Symbols:**

```
ffffffff81778780-ffffffff817789c1: hpet_ioctl_ieon (STB_LOCAL)
ffffffff81778d61-ffffffff81778d75: hpet_ioctl_ieon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int hpet_ioctl_ieon(struct hpet_dev *devp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (0)
Location: drivers/char/hpet.c:453
Inline: False
```
**Symbols:**

```
ffffffff81793260-ffffffff817934a1: hpet_ioctl_ieon (STB_LOCAL)
ffffffff81c08956-ffffffff81c0896a: hpet_ioctl_ieon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int hpet_ioctl_ieon(struct hpet_dev *devp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (0)
Location: drivers/char/hpet.c:453
Inline: False
```
**Symbols:**

```
ffffffff81775f60-ffffffff817761a2: hpet_ioctl_ieon (STB_LOCAL)
ffffffff81bfa4f8-ffffffff81bfa50c: hpet_ioctl_ieon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hpet_ioctl_ieon(struct hpet_dev *devp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (0)
Location: drivers/char/hpet.c:453
Inline: False
```
**Symbols:**

```
ffffffff817fbcd0-ffffffff817fbf34: hpet_ioctl_ieon (STB_LOCAL)
ffffffff81cfaf1d-ffffffff81cfaf83: hpet_ioctl_ieon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hpet_ioctl_ieon(struct hpet_dev *devp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (0)
Location: drivers/char/hpet.c:438
Inline: False
Direct callers:
  - drivers/char/hpet.c:hpet_ioctl_common
```
**Symbols:**

```
ffffffff8193a2a0-ffffffff8193a4f9: hpet_ioctl_ieon (STB_LOCAL)
ffffffff81ec3771-ffffffff81ec37d7: hpet_ioctl_ieon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int hpet_ioctl_ieon(struct hpet_dev *devp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (0)
Location: drivers/char/hpet.c:438
Inline: False
Direct callers:
  - drivers/char/hpet.c:hpet_ioctl_common
```
**Symbols:**

```
ffffffff81a9a6c0-ffffffff81a9a92e: hpet_ioctl_ieon (STB_LOCAL)
ffffffff82096735-ffffffff82096787: hpet_ioctl_ieon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hpet_ioctl_ieon(struct hpet_dev *devp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (0)
Location: drivers/char/hpet.c:438
Inline: False
Direct callers:
  - drivers/char/hpet.c:hpet_ioctl_common
```
**Symbols:**

```
ffffffff81ae5f60-ffffffff81ae61cd: hpet_ioctl_ieon (STB_LOCAL)
ffffffff8211767d-ffffffff821176cf: hpet_ioctl_ieon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int hpet_ioctl_ieon(struct hpet_dev *devp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (0)
Location: drivers/char/hpet.c:419
Inline: False
Direct callers:
  - drivers/char/hpet.c:hpet_ioctl_common
```
**Symbols:**

```
ffffffff81b392f0-ffffffff81b3955d: hpet_ioctl_ieon (STB_LOCAL)
ffffffff821f53f2-ffffffff821f5444: hpet_ioctl_ieon.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff81689777)
Location: drivers/char/hpet.c:453
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff816671f7)
Location: drivers/char/hpet.c:453
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff816b79e7)
Location: drivers/char/hpet.c:453
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff816d2247)
Location: drivers/char/hpet.c:453
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
