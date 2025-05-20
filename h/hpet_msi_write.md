# Function: <code>hpet_msi_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void hpet_msi_write(struct hpet_dev *hdev, struct msi_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81062ec0)
Location: arch/x86/kernel/hpet.c:475
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
**Symbols:**

```
ffffffff81062ec0-ffffffff81062efe: hpet_msi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void hpet_msi_write(struct hpet_dev *hdev, struct msi_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81062b50)
Location: arch/x86/kernel/hpet.c:475
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
**Symbols:**

```
ffffffff81062b50-ffffffff81062b8e: hpet_msi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void hpet_msi_write(struct hpet_dev *hdev, struct msi_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81065ce0)
Location: arch/x86/kernel/hpet.c:476
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
**Symbols:**

```
ffffffff81065ce0-ffffffff81065d1e: hpet_msi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_write(struct hpet_dev *hdev, struct msi_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8106410c)
Location: arch/x86/kernel/hpet.c:465
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_resume
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
**Symbols:**

```
ffffffff81064db0-ffffffff81064dee: hpet_msi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_write(struct hpet_dev *hdev, struct msi_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8106828c)
Location: arch/x86/kernel/hpet.c:465
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_resume
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
**Symbols:**

```
ffffffff81068f40-ffffffff81068f7e: hpet_msi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_write(struct hpet_dev *hdev, struct msi_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8106addc)
Location: arch/x86/kernel/hpet.c:466
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_resume
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
**Symbols:**

```
ffffffff8106b9e0-ffffffff8106ba1e: hpet_msi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_write(struct hpet_dev *hdev, struct msi_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81070b6c)
Location: arch/x86/kernel/hpet.c:462
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_resume
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
**Symbols:**

```
ffffffff81071770-ffffffff810717ae: hpet_msi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_write(struct hpet_channel *hc, struct msi_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81074bbc)
Location: arch/x86/kernel/hpet.c:492
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
**Symbols:**

```
ffffffff810755e0-ffffffff8107561e: hpet_msi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_write(struct hpet_channel *hc, struct msi_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81075b8c)
Location: arch/x86/kernel/hpet.c:492
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
**Symbols:**

```
ffffffff810765b0-ffffffff810765ee: hpet_msi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_write(struct hpet_channel *hc, struct msi_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107d30c)
Location: arch/x86/kernel/hpet.c:492
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
**Symbols:**

```
ffffffff8107d870-ffffffff8107d8ae: hpet_msi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107d27c)
Location: arch/x86/kernel/hpet.c:492
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107e37c)
Location: arch/x86/kernel/hpet.c:492
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8108cebc)
Location: arch/x86/kernel/hpet.c:493
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8109db1b)
Location: arch/x86/kernel/hpet.c:493
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810b4ceb)
Location: arch/x86/kernel/hpet.c:493
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810b7dbb)
Location: arch/x86/kernel/hpet.c:493
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810bf1fb)
Location: arch/x86/kernel/hpet.c:493
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
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
void hpet_msi_write(struct hpet_channel *hc, struct msi_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81074b8c)
Location: arch/x86/kernel/hpet.c:492
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
**Symbols:**

```
ffffffff810755b0-ffffffff810755ee: hpet_msi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_write(struct hpet_channel *hc, struct msi_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81064bbc)
Location: arch/x86/kernel/hpet.c:492
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
**Symbols:**

```
ffffffff810655a0-ffffffff810655de: hpet_msi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_write(struct hpet_channel *hc, struct msi_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81074b3c)
Location: arch/x86/kernel/hpet.c:492
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
**Symbols:**

```
ffffffff81075560-ffffffff8107559e: hpet_msi_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_write(struct hpet_channel *hc, struct msi_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81076b9c)
Location: arch/x86/kernel/hpet.c:492
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
Direct callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
**Symbols:**

```
ffffffff810775c0-ffffffff810775fe: hpet_msi_write (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct hpet_channel *hc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct hpet_dev *hdev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
