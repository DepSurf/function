# Function: <code>compat_tty_tiocsserial</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
int compat_tty_tiocsserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162bc70)
Location: drivers/tty/tty_io.c:2694
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff8162bc70-ffffffff8162bda9: compat_tty_tiocsserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int compat_tty_tiocsserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8165fbd0)
Location: drivers/tty/tty_io.c:2698
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff8165fbd0-ffffffff8165fd11: compat_tty_tiocsserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int compat_tty_tiocsserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816821f0)
Location: drivers/tty/tty_io.c:2698
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff816821f0-ffffffff81682331: compat_tty_tiocsserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int compat_tty_tiocsserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81733750)
Location: drivers/tty/tty_io.c:2697
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff81733750-ffffffff81733891: compat_tty_tiocsserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int compat_tty_tiocsserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8174f890)
Location: drivers/tty/tty_io.c:2785
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff8174f890-ffffffff8174f9d1: compat_tty_tiocsserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int compat_tty_tiocsserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81733830)
Location: drivers/tty/tty_io.c:2846
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff81733830-ffffffff817338eb: compat_tty_tiocsserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int compat_tty_tiocsserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b41a0)
Location: drivers/tty/tty_io.c:2846
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff817b41a0-ffffffff817b425b: compat_tty_tiocsserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int compat_tty_tiocsserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818efeb0)
Location: drivers/tty/tty_io.c:2819
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff818efeb0-ffffffff818effc2: compat_tty_tiocsserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int compat_tty_tiocsserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a47fa0)
Location: drivers/tty/tty_io.c:2818
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff81a47fa0-ffffffff81a480b2: compat_tty_tiocsserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int compat_tty_tiocsserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a92140)
Location: drivers/tty/tty_io.c:2827
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff81a92140-ffffffff81a92252: compat_tty_tiocsserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int compat_tty_tiocsserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae4b20)
Location: drivers/tty/tty_io.c:2844
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff81ae4b20-ffffffff81ae4c32: compat_tty_tiocsserial (STB_LOCAL)
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
int compat_tty_tiocsserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff800010850ce8)
Location: drivers/tty/tty_io.c:2698
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffff800010850ce8-ffff800010850f48: compat_tty_tiocsserial (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int compat_tty_tiocsserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008ecee0)
Location: drivers/tty/tty_io.c:2698
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
c0000000008ecee0-c0000000008ed06c: compat_tty_tiocsserial (STB_LOCAL)
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
int compat_tty_tiocsserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81647c70)
Location: drivers/tty/tty_io.c:2698
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff81647c70-ffffffff81647db1: compat_tty_tiocsserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int compat_tty_tiocsserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816280d0)
Location: drivers/tty/tty_io.c:2698
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff816280d0-ffffffff81628211: compat_tty_tiocsserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int compat_tty_tiocsserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81676030)
Location: drivers/tty/tty_io.c:2698
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff81676030-ffffffff81676171: compat_tty_tiocsserial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int compat_tty_tiocsserial(struct tty_struct *tty, struct serial_struct32 *ss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81690750)
Location: drivers/tty/tty_io.c:2698
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
```
**Symbols:**

```
ffffffff81690750-ffffffff81690891: compat_tty_tiocsserial (STB_LOCAL)
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
