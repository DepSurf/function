# Function: <code>security_validtrans_handle_fail</code>

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
In security/selinux/ss/services.c (ffffffff813576f8)
Location: security/selinux/ss/services.c:753
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_validate_transition
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
In security/selinux/ss/services.c (ffffffff8138c8f7)
Location: security/selinux/ss/services.c:727
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
In security/selinux/ss/services.c (ffffffff813a3507)
Location: security/selinux/ss/services.c:727
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
In security/selinux/ss/services.c (ffffffff813b9737)
Location: security/selinux/ss/services.c:739
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
In security/selinux/ss/services.c (ffffffff813df8c7)
Location: security/selinux/ss/services.c:741
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
In security/selinux/ss/services.c (ffffffff8140fc92)
Location: security/selinux/ss/services.c:730
Inline: True
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
In security/selinux/ss/services.c (ffffffff8142c068)
Location: security/selinux/ss/services.c:727
Inline: True
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
In security/selinux/ss/services.c (ffffffff81459991)
Location: security/selinux/ss/services.c:718
Inline: True
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
In security/selinux/ss/services.c (ffffffff81473731)
Location: security/selinux/ss/services.c:718
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_validtrans_handle_fail(struct selinux_state *state, struct sidtab_entry *oentry, struct sidtab_entry *nentry, struct sidtab_entry *tentry, u16 tclass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814c7e90)
Location: security/selinux/ss/services.c:723
Inline: False
```
**Symbols:**

```
ffffffff814c7e90-ffffffff814c7fd4: security_validtrans_handle_fail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_validtrans_handle_fail(struct selinux_state *state, struct selinux_policy *policy, struct sidtab_entry *oentry, struct sidtab_entry *nentry, struct sidtab_entry *tentry, u16 tclass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e5cb0)
Location: security/selinux/ss/services.c:722
Inline: False
```
**Symbols:**

```
ffffffff814e5cb0-ffffffff814e5de9: security_validtrans_handle_fail (STB_LOCAL)
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
In security/selinux/ss/services.c (ffffffff814ed271)
Location: security/selinux/ss/services.c:724
Inline: True
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
In security/selinux/ss/services.c (ffffffff815476a1)
Location: security/selinux/ss/services.c:724
Inline: True
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
In security/selinux/ss/services.c (ffffffff815e0a6e)
Location: security/selinux/ss/services.c:722
Inline: True
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
In security/selinux/ss/services.c (ffffffff8168f301)
Location: security/selinux/ss/services.c:716
Inline: True
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
In security/selinux/ss/services.c (ffffffff816c6ed9)
Location: security/selinux/ss/services.c:716
Inline: True
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
In security/selinux/ss/services.c (ffffffff81703939)
Location: security/selinux/ss/services.c:716
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
In security/selinux/ss/services.c (ffff8000105630ec)
Location: security/selinux/ss/services.c:718
Inline: True
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
In security/selinux/ss/services.c (c07174ec)
Location: security/selinux/ss/services.c:718
Inline: True
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
In security/selinux/ss/services.c (c0000000006c48d0)
Location: security/selinux/ss/services.c:718
Inline: True
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
In security/selinux/ss/services.c (ffffffe0003ba34a)
Location: security/selinux/ss/services.c:718
Inline: True
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
In security/selinux/ss/services.c (ffffffff8146bd11)
Location: security/selinux/ss/services.c:718
Inline: True
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
In security/selinux/ss/services.c (ffffffff8145c741)
Location: security/selinux/ss/services.c:718
Inline: True
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
In security/selinux/ss/services.c (ffffffff81467db1)
Location: security/selinux/ss/services.c:718
Inline: True
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
In security/selinux/ss/services.c (ffffffff8147f58f)
Location: security/selinux/ss/services.c:718
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct selinux_policy *policy</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, oentry, nentry, tentry, tclass</code> ➡️ <code>state, policy, oentry, nentry, tentry, tclass</code>
</li>
</ul>
</details>
</li>
</ul>
