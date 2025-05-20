# Function: <code>aa_mk_null_file</code>

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
In security/apparmor/apparmorfs.c (ffffffff81f99349)
Location: security/apparmor/apparmorfs.c:1205
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
In security/apparmor/apparmorfs.c (ffffffff81fc40bc)
Location: security/apparmor/apparmorfs.c:1702
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
In security/apparmor/apparmorfs.c (ffffffff82000aeb)
Location: security/apparmor/apparmorfs.c:1819
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
In security/apparmor/apparmorfs.c (ffffffff820e431e)
Location: security/apparmor/apparmorfs.c:2342
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
In security/apparmor/apparmorfs.c (ffffffff826ecfce)
Location: security/apparmor/apparmorfs.c:2406
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
In security/apparmor/apparmorfs.c (ffffffff82717311)
Location: security/apparmor/apparmorfs.c:2412
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
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
In security/apparmor/apparmorfs.c (ffffffff828cedd6)
Location: security/apparmor/apparmorfs.c:2476
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
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
In security/apparmor/apparmorfs.c (ffffffff828e8861)
Location: security/apparmor/apparmorfs.c:2481
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
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
In security/apparmor/apparmorfs.c (ffffffff828f134d)
Location: security/apparmor/apparmorfs.c:2449
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aa_mk_null_file(struct dentry *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814f03ef)
Location: security/apparmor/apparmorfs.c:2504
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff814f03ef-ffffffff814f056c: aa_mk_null_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aa_mk_null_file(struct dentry *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81bf14bd)
Location: security/apparmor/apparmorfs.c:2501
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff81bf14bd-ffffffff81bf163a: aa_mk_null_file (STB_LOCAL)
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
In security/apparmor/apparmorfs.c (ffffffff831fe277)
Location: security/apparmor/apparmorfs.c:2502
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
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
In security/apparmor/apparmorfs.c (ffffffff832e5589)
Location: security/apparmor/apparmorfs.c:2502
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
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
In security/apparmor/apparmorfs.c (ffffffff8349c2f7)
Location: security/apparmor/apparmorfs.c:2533
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
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
In security/apparmor/apparmorfs.c (ffffffff83ed34d6)
Location: security/apparmor/apparmorfs.c:2725
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
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
In security/apparmor/apparmorfs.c (ffffffff836f8550)
Location: security/apparmor/apparmorfs.c:2796
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
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
In security/apparmor/apparmorfs.c (ffffffff8392b93e)
Location: security/apparmor/apparmorfs.c:2798
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
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
In security/apparmor/apparmorfs.c (ffff80001146b508)
Location: security/apparmor/apparmorfs.c:2449
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
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
In security/apparmor/apparmorfs.c (c15441b0)
Location: security/apparmor/apparmorfs.c:2449
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
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
In security/apparmor/apparmorfs.c (c000000001399f2c)
Location: security/apparmor/apparmorfs.c:2449
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
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
In security/apparmor/apparmorfs.c (ffffffe00002655e)
Location: security/apparmor/apparmorfs.c:2449
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
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
In security/apparmor/apparmorfs.c (ffffffff828da201)
Location: security/apparmor/apparmorfs.c:2449
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
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
In security/apparmor/apparmorfs.c (ffffffff828d291d)
Location: security/apparmor/apparmorfs.c:2449
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
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
In security/apparmor/apparmorfs.c (ffffffff828ecf75)
Location: security/apparmor/apparmorfs.c:2449
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
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
In security/apparmor/apparmorfs.c (ffffffff828f2397)
Location: security/apparmor/apparmorfs.c:2449
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
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
