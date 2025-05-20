# Function: <code>decode_eisa_sig</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/eisa/eisa-bus.c (ffffffff828edfb5)
Location: drivers/eisa/eisa-bus.c:76
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
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
In drivers/eisa/eisa-bus.c (ffffffff82909444)
Location: drivers/eisa/eisa-bus.c:75
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
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
In drivers/eisa/eisa-bus.c (ffffffff82912e49)
Location: drivers/eisa/eisa-bus.c:75
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *decode_eisa_sig(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/eisa/eisa-bus.c (ffffffff82d25aad)
Location: drivers/eisa/eisa-bus.c:75
Inline: False
Direct callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
**Symbols:**

```
ffffffff82d25aad-ffffffff82d25b63: decode_eisa_sig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *decode_eisa_sig(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/eisa/eisa-bus.c (ffffffff8301404e)
Location: drivers/eisa/eisa-bus.c:75
Inline: False
Direct callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
```
**Symbols:**

```
ffffffff8301404e-ffffffff83014104: decode_eisa_sig (STB_LOCAL)
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
In drivers/eisa/eisa-bus.c (ffffffff8321f173)
Location: drivers/eisa/eisa-bus.c:75
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
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
In drivers/eisa/eisa-bus.c (ffffffff833088b7)
Location: drivers/eisa/eisa-bus.c:75
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
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
In drivers/eisa/eisa-bus.c (ffffffff834c1e8a)
Location: drivers/eisa/eisa-bus.c:75
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
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
In drivers/eisa/eisa-bus.c (ffffffff83f016bd)
Location: drivers/eisa/eisa-bus.c:75
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
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
In drivers/eisa/eisa-bus.c (ffffffff8372756d)
Location: drivers/eisa/eisa-bus.c:75
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
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
In drivers/eisa/eisa-bus.c (ffffffff8395b5ad)
Location: drivers/eisa/eisa-bus.c:75
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
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
In drivers/eisa/eisa-bus.c (ffffffff828f8c5d)
Location: drivers/eisa/eisa-bus.c:75
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
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
In drivers/eisa/eisa-bus.c (ffffffff828f0746)
Location: drivers/eisa/eisa-bus.c:75
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
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
In drivers/eisa/eisa-bus.c (ffffffff8290d495)
Location: drivers/eisa/eisa-bus.c:75
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
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
In drivers/eisa/eisa-bus.c (ffffffff82913eab)
Location: drivers/eisa/eisa-bus.c:75
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_init_device
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
</ul>
