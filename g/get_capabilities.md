# Function: <code>get_capabilities</code>

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
In drivers/scsi/sr.c (ffffffff815c0a94)
Location: drivers/scsi/sr.c:832
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
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
In drivers/scsi/sr.c (ffffffff81619234)
Location: drivers/scsi/sr.c:831
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
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
In drivers/scsi/sr.c (ffffffff81649ec4)
Location: drivers/scsi/sr.c:831
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
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
In drivers/scsi/sr.c (ffffffff8165e99d)
Location: drivers/scsi/sr.c:834
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
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
In drivers/scsi/sr.c (ffffffff816c7db2)
Location: drivers/scsi/sr.c:834
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
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
In drivers/scsi/sr.c (ffffffff81704767)
Location: drivers/scsi/sr.c:860
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
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
In drivers/scsi/sr.c (ffffffff81726bd7)
Location: drivers/scsi/sr.c:861
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
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
In drivers/scsi/sr.c (ffffffff8176230a)
Location: drivers/scsi/sr.c:862
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
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
In drivers/scsi/sr.c (ffffffff817862fa)
Location: drivers/scsi/sr.c:862
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void get_capabilities(struct scsi_cd *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr.c (ffffffff8184a370)
Location: drivers/scsi/sr.c:907
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff8184a370-ffffffff8184a672: get_capabilities (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void get_capabilities(struct scsi_cd *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr.c (ffffffff8185a870)
Location: drivers/scsi/sr.c:879
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff8185a870-ffffffff8185ab72: get_capabilities (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void get_capabilities(struct scsi_cd *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr.c (ffffffff8183d6f0)
Location: drivers/scsi/sr.c:881
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff8183d6f0-ffffffff8183d9d6: get_capabilities (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void get_capabilities(struct scsi_cd *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr.c (ffffffff818ca1c0)
Location: drivers/scsi/sr.c:833
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff818ca1c0-ffffffff818ca499: get_capabilities (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_capabilities(struct scsi_cd *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr.c (ffffffff81a17660)
Location: drivers/scsi/sr.c:798
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff81a17660-ffffffff81a1797f: get_capabilities (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_capabilities(struct scsi_cd *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr.c (ffffffff81b98560)
Location: drivers/scsi/sr.c:798
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff81b98560-ffffffff81b9887f: get_capabilities (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_capabilities(struct scsi_cd *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr.c (ffffffff81beeb00)
Location: drivers/scsi/sr.c:796
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff81beeb00-ffffffff81beee12: get_capabilities (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_capabilities(struct scsi_cd *cd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr.c (ffffffff81c44240)
Location: drivers/scsi/sr.c:797
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff81c44240-ffffffff81c44581: get_capabilities (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr.c (ffff80001098ca00)
Location: drivers/scsi/sr.c:862
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
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
In drivers/scsi/sr.c (c0a5ef8c)
Location: drivers/scsi/sr.c:862
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr.c (c000000000a4e038)
Location: drivers/scsi/sr.c:862
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
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
In drivers/scsi/sr.c (ffffffe0005f152a)
Location: drivers/scsi/sr.c:862
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
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
In drivers/scsi/sr.c (ffffffff8173a9ea)
Location: drivers/scsi/sr.c:862
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
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
In drivers/scsi/sr.c (ffffffff8171c68a)
Location: drivers/scsi/sr.c:862
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
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
In drivers/scsi/sr.c (ffffffff8177b17a)
Location: drivers/scsi/sr.c:862
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
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
In drivers/scsi/sr.c (ffffffff81794ce8)
Location: drivers/scsi/sr.c:862
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
