# Function: <code>lsm_set_blob_sizes</code>

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
In security/security.c (ffffffff828cd71d)
Location: security/security.c:167
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff828e7150)
Location: security/security.c:163
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff828efb8a)
Location: security/security.c:164
Inline: True
Inline callers:
  - security/security.c:prepare_lsm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff82d04dfa)
Location: security/security.c:196
Inline: True
Inline callers:
  - security/security.c:prepare_lsm
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
In security/security.c (ffffffff82ff21c7)
Location: security/security.c:198
Inline: True
Inline callers:
  - security/security.c:prepare_lsm
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
In security/security.c (ffffffff831fcb51)
Location: security/security.c:199
Inline: True
Inline callers:
  - security/security.c:prepare_lsm
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
In security/security.c (ffffffff832e3c5d)
Location: security/security.c:199
Inline: True
Inline callers:
  - security/security.c:prepare_lsm
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
In security/security.c (ffffffff8349a0f6)
Location: security/security.c:203
Inline: True
Inline callers:
  - security/security.c:prepare_lsm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void lsm_set_blob_sizes(struct lsm_blob_sizes *needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff83ecfce0)
Location: security/security.c:208
Inline: False
Direct callers:
  - security/security.c:prepare_lsm
```
**Symbols:**

```
ffffffff83ecfce0-ffffffff83ecfe18: lsm_set_blob_sizes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void lsm_set_blob_sizes(struct lsm_blob_sizes *needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff836f4da0)
Location: security/security.c:209
Inline: False
Direct callers:
  - security/security.c:prepare_lsm
```
**Symbols:**

```
ffffffff836f4da0-ffffffff836f4ed8: lsm_set_blob_sizes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void lsm_set_blob_sizes(struct lsm_blob_sizes *needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff83928030)
Location: security/security.c:215
Inline: False
Direct callers:
  - security/security.c:prepare_lsm
```
**Symbols:**

```
ffffffff83928030-ffffffff839282b1: lsm_set_blob_sizes (STB_LOCAL)
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
In security/security.c (ffff800011469a08)
Location: security/security.c:164
Inline: True
Inline callers:
  - security/security.c:prepare_lsm
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
In security/security.c (c1542578)
Location: security/security.c:164
Inline: True
Inline callers:
  - security/security.c:prepare_lsm
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
In security/security.c (c000000001397c70)
Location: security/security.c:164
Inline: True
Inline callers:
  - security/security.c:prepare_lsm
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
In security/security.c (ffffffe000024b74)
Location: security/security.c:164
Inline: True
Inline callers:
  - security/security.c:prepare_lsm
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
In security/security.c (ffffffff828d8a3e)
Location: security/security.c:164
Inline: True
Inline callers:
  - security/security.c:prepare_lsm
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
In security/security.c (ffffffff828d115a)
Location: security/security.c:164
Inline: True
Inline callers:
  - security/security.c:prepare_lsm
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
In security/security.c (ffffffff828eb7be)
Location: security/security.c:164
Inline: True
Inline callers:
  - security/security.c:prepare_lsm
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
In security/security.c (ffffffff828f0bd4)
Location: security/security.c:164
Inline: True
Inline callers:
  - security/security.c:prepare_lsm
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
