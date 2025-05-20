# Function: <code>kpp_request_set_output</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff81396084)
Location: include/crypto/kpp.h:235
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
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
In security/keys/dh.c (ffffffff813bb806)
Location: include/crypto/kpp.h:245
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
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
In security/keys/dh.c (ffffffff813ec64f)
Location: include/crypto/kpp.h:245
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
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
In security/keys/dh.c (ffffffff81407206)
Location: include/crypto/kpp.h:245
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
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
In security/keys/dh.c (ffffffff8143436f)
Location: include/crypto/kpp.h:240
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
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
In security/keys/dh.c (ffffffff8144e0bf)
Location: include/crypto/kpp.h:240
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
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
In security/keys/dh.c (ffffffff814a032e)
Location: include/crypto/kpp.h:240
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
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
In security/keys/dh.c (ffffffff814bdd3e)
Location: include/crypto/kpp.h:240
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
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
In security/keys/dh.c (ffffffff814c3bae)
Location: include/crypto/kpp.h:242
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
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
In security/keys/dh.c (ffffffff8151c57e)
Location: include/crypto/kpp.h:242
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff815af62f)
Location: include/crypto/kpp.h:242
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (0)
Location: include/crypto/kpp.h:242
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff81659e5e)
Location: include/crypto/kpp.h:245
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (0)
Location: include/crypto/kpp.h:245
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff81692804)
Location: include/crypto/kpp.h:268
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (0)
Location: include/crypto/kpp.h:268
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff816cedd4)
Location: include/crypto/kpp.h:268
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In crypto/dh.c (0)
Location: include/crypto/kpp.h:268
Inline: True
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
In security/keys/dh.c (0)
Location: include/crypto/kpp.h:240
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
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
In security/keys/dh.c (c06ef2ec)
Location: include/crypto/kpp.h:240
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
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
In security/keys/dh.c (c000000000687508)
Location: include/crypto/kpp.h:240
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
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
In security/keys/dh.c (ffffffe0003975a6)
Location: include/crypto/kpp.h:240
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
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
In security/keys/dh.c (ffffffff8144669f)
Location: include/crypto/kpp.h:240
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
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
In security/keys/dh.c (ffffffff814370ef)
Location: include/crypto/kpp.h:240
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
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
In security/keys/dh.c (ffffffff8144273f)
Location: include/crypto/kpp.h:240
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
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
In security/keys/dh.c (ffffffff81459a6f)
Location: include/crypto/kpp.h:240
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
</details>
</li>
</ul>

## Differences
