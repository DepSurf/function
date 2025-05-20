# Function: <code>ata_eh_revalidate_and_attach</code>

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
In drivers/ata/libata-eh.c (ffffffff815d8d3c)
Location: drivers/ata/libata-eh.c:3101
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff81632a3d)
Location: drivers/ata/libata-eh.c:3192
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff81663b8d)
Location: drivers/ata/libata-eh.c:3192
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff81677eb5)
Location: drivers/ata/libata-eh.c:3147
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff816e14f5)
Location: drivers/ata/libata-eh.c:3145
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff8171e320)
Location: drivers/ata/libata-eh.c:3123
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff81740c00)
Location: drivers/ata/libata-eh.c:3119
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ata_eh_revalidate_and_attach(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (0)
Location: drivers/ata/libata-eh.c:3104
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81779ff0-ffffffff8177a336: ata_eh_revalidate_and_attach (STB_LOCAL)
ffffffff8177dec3-ffffffff8177ded6: ata_eh_revalidate_and_attach.cold (STB_LOCAL)
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
In drivers/ata/libata-eh.c (ffffffff817a05a2)
Location: drivers/ata/libata-eh.c:3104
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ata_eh_revalidate_and_attach(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81862b30)
Location: drivers/ata/libata-eh.c:2906
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81862b30-ffffffff81862ea1: ata_eh_revalidate_and_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ata_eh_revalidate_and_attach(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81871940)
Location: drivers/ata/libata-eh.c:2906
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81871940-ffffffff81871cb1: ata_eh_revalidate_and_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ata_eh_revalidate_and_attach(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81854040)
Location: drivers/ata/libata-eh.c:2907
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81854040-ffffffff818543b6: ata_eh_revalidate_and_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ata_eh_revalidate_and_attach(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (0)
Location: drivers/ata/libata-eh.c:2914
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff818e2390-ffffffff818e283a: ata_eh_revalidate_and_attach (STB_LOCAL)
ffffffff81d0e8b2-ffffffff81d0e8ee: ata_eh_revalidate_and_attach.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ata_eh_revalidate_and_attach(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (0)
Location: drivers/ata/libata-eh.c:2919
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81a33560-ffffffff81a33a03: ata_eh_revalidate_and_attach (STB_LOCAL)
ffffffff81ed8810-ffffffff81ed884c: ata_eh_revalidate_and_attach.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ata_eh_revalidate_and_attach(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (0)
Location: drivers/ata/libata-eh.c:2924
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81bb7d00-ffffffff81bb81b1: ata_eh_revalidate_and_attach (STB_LOCAL)
ffffffff8209c871-ffffffff8209c8ad: ata_eh_revalidate_and_attach.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ata_eh_revalidate_and_attach(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (0)
Location: drivers/ata/libata-eh.c:3034
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81c0f570-ffffffff81c0fa58: ata_eh_revalidate_and_attach (STB_LOCAL)
ffffffff8211d786-ffffffff8211d7bc: ata_eh_revalidate_and_attach.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ata_eh_revalidate_and_attach(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-eh.c (0)
Location: drivers/ata/libata-eh.c:3033
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81c647b0-ffffffff81c64c98: ata_eh_revalidate_and_attach (STB_LOCAL)
ffffffff821fb7be-ffffffff821fb7f4: ata_eh_revalidate_and_attach.cold (STB_LOCAL)
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
int ata_eh_revalidate_and_attach(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffff8000109a94a0)
Location: drivers/ata/libata-eh.c:3104
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffff8000109a94a0-ffff8000109a9868: ata_eh_revalidate_and_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c0a7b860)
Location: drivers/ata/libata-eh.c:3104
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ata_eh_revalidate_and_attach(struct ata_link *link, struct ata_device **r_failed_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c000000000a6fe40)
Location: drivers/ata/libata-eh.c:3104
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
c000000000a6fe40-c000000000a70308: ata_eh_revalidate_and_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffe000609506)
Location: drivers/ata/libata-eh.c:3104
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
</details>
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
In drivers/ata/libata-eh.c (ffffffff81765689)
Location: drivers/ata/libata-eh.c:3104
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff817454e9)
Location: drivers/ata/libata-eh.c:3104
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff81795422)
Location: drivers/ata/libata-eh.c:3104
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
In drivers/ata/libata-eh.c (ffffffff817af292)
Location: drivers/ata/libata-eh.c:3104
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
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
<b>Arch</b>
<ul>
</ul>
