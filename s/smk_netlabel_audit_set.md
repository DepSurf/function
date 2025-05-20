# Function: <code>smk_netlabel_audit_set</code>

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
In security/smack/smackfs.c (ffffffff81363e48)
Location: security/smack/smackfs.c:193
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_cipso_doi
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_write_net4addr
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
In security/smack/smackfs.c (ffffffff8139bf54)
Location: security/smack/smackfs.c:193
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smackfs.c (ffffffff813b26b4)
Location: security/smack/smackfs.c:193
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smackfs.c (ffffffff813c90d9)
Location: security/smack/smackfs.c:194
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smackfs.c (ffffffff813ef569)
Location: security/smack/smackfs.c:194
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smackfs.c (ffffffff814205c7)
Location: security/smack/smackfs.c:194
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smackfs.c (ffffffff8143c803)
Location: security/smack/smackfs.c:194
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smackfs.c (ffffffff8146a409)
Location: security/smack/smackfs.c:182
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smackfs.c (ffffffff814841e9)
Location: security/smack/smackfs.c:182
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void smk_netlabel_audit_set(struct netlbl_audit *nap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff814d7910)
Location: security/smack/smackfs.c:182
Inline: False
Direct callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
**Symbols:**

```
ffffffff814d7910-ffffffff814d7967: smk_netlabel_audit_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void smk_netlabel_audit_set(struct netlbl_audit *nap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff814f4e90)
Location: security/smack/smackfs.c:182
Inline: False
Direct callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
**Symbols:**

```
ffffffff814f4e90-ffffffff814f4ee8: smk_netlabel_audit_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void smk_netlabel_audit_set(struct netlbl_audit *nap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff814fbe00)
Location: security/smack/smackfs.c:182
Inline: False
Direct callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
**Symbols:**

```
ffffffff814fbe00-ffffffff814fbe58: smk_netlabel_audit_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void smk_netlabel_audit_set(struct netlbl_audit *nap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff81556a60)
Location: security/smack/smackfs.c:182
Inline: False
Direct callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
```
**Symbols:**

```
ffffffff81556a60-ffffffff81556ade: smk_netlabel_audit_set (STB_LOCAL)
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
In security/smack/smackfs.c (ffffffff815f3f01)
Location: security/smack/smackfs.c:183
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smackfs.c (ffffffff816a4891)
Location: security/smack/smackfs.c:183
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smackfs.c (ffffffff816dcbe1)
Location: security/smack/smackfs.c:183
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smackfs.c (ffffffff81719b42)
Location: security/smack/smackfs.c:183
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smackfs.c (ffff8000105760b8)
Location: security/smack/smackfs.c:182
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smackfs.c (c07290b8)
Location: security/smack/smackfs.c:182
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smackfs.c (c0000000006df974)
Location: security/smack/smackfs.c:182
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smackfs.c (ffffffe0003c8eca)
Location: security/smack/smackfs.c:182
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smackfs.c (ffffffff8147c7c9)
Location: security/smack/smackfs.c:182
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smackfs.c (ffffffff8146d1e9)
Location: security/smack/smackfs.c:182
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smackfs.c (ffffffff81478869)
Location: security/smack/smackfs.c:182
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
In security/smack/smackfs.c (ffffffff81490319)
Location: security/smack/smackfs.c:182
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_unlbl_ambient
  - security/smack/smackfs.c:smk_cipso_doi
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
</ul>
