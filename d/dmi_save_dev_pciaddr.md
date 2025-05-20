# Function: <code>dmi_save_dev_pciaddr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff81fe2d1f)
Location: drivers/firmware/dmi_scan.c:324
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffffffff81fe24bf-ffffffff81fe2561: dmi_save_dev_pciaddr.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff82020aee)
Location: drivers/firmware/dmi_scan.c:324
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffffffff8202029c-ffffffff8202033e: dmi_save_dev_pciaddr.part.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char *name, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff82102b4c)
Location: drivers/firmware/dmi_scan.c:330
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffffffff82102b4c-ffffffff82102c15: dmi_save_dev_pciaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char *name, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff8270c228)
Location: drivers/firmware/dmi_scan.c:330
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffffffff8270c228-ffffffff8270c2f1: dmi_save_dev_pciaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char *name, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff827365b3)
Location: drivers/firmware/dmi_scan.c:322
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffffffff827365b3-ffffffff8273667c: dmi_save_dev_pciaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char *name, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff828f04df)
Location: drivers/firmware/dmi_scan.c:322
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffffffff828f04df-ffffffff828f05a8: dmi_save_dev_pciaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char *name, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff8290bc02)
Location: drivers/firmware/dmi_scan.c:323
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffffffff8290bc02-ffffffff8290bcc7: dmi_save_dev_pciaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char *name, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff829155d1)
Location: drivers/firmware/dmi_scan.c:323
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffffffff829155d1-ffffffff82915696: dmi_save_dev_pciaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char *name, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff82d27a4f)
Location: drivers/firmware/dmi_scan.c:356
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffffffff82d27a4f-ffffffff82d27b0e: dmi_save_dev_pciaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char *name, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff83016167)
Location: drivers/firmware/dmi_scan.c:356
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffffffff83016167-ffffffff83016226: dmi_save_dev_pciaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char *name, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff83221110)
Location: drivers/firmware/dmi_scan.c:357
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffffffff83221110-ffffffff832211cf: dmi_save_dev_pciaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char *name, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff8330ab64)
Location: drivers/firmware/dmi_scan.c:357
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffffffff8330ab64-ffffffff8330ac23: dmi_save_dev_pciaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char *name, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff834c4471)
Location: drivers/firmware/dmi_scan.c:357
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffffffff834c4471-ffffffff834c4547: dmi_save_dev_pciaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char *name, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff83f046c0)
Location: drivers/firmware/dmi_scan.c:357
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffffffff83f046c0-ffffffff83f0479b: dmi_save_dev_pciaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char *name, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff8372a680)
Location: drivers/firmware/dmi_scan.c:357
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffffffff8372a680-ffffffff8372a75b: dmi_save_dev_pciaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char *name, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff8395e640)
Location: drivers/firmware/dmi_scan.c:357
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffffffff8395e640-ffffffff8395e71b: dmi_save_dev_pciaddr (STB_LOCAL)
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
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char *name, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffff8000114a37bc)
Location: drivers/firmware/dmi_scan.c:323
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffff8000114a37bc-ffff8000114a3884: dmi_save_dev_pciaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char *name, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (c15a5f14)
Location: drivers/firmware/dmi_scan.c:323
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
c15a5f14-c15a5fc0: dmi_save_dev_pciaddr (STB_LOCAL)
```
</details>
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
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char *name, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff828fab25)
Location: drivers/firmware/dmi_scan.c:323
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffffffff828fab25-ffffffff828fabea: dmi_save_dev_pciaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char *name, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff828f23c1)
Location: drivers/firmware/dmi_scan.c:323
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffffffff828f23c1-ffffffff828f2486: dmi_save_dev_pciaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char *name, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff8290fc06)
Location: drivers/firmware/dmi_scan.c:323
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffffffff8290fc06-ffffffff8290fccb: dmi_save_dev_pciaddr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dmi_save_dev_pciaddr(int instance, int segment, int bus, int devfn, const char *name, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/dmi_scan.c (ffffffff82916633)
Location: drivers/firmware/dmi_scan.c:323
Inline: False
Direct callers:
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
```
**Symbols:**

```
ffffffff82916633-ffffffff829166f8: dmi_save_dev_pciaddr (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
