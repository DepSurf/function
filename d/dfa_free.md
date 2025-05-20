# Function: <code>dfa_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dfa_free(struct aa_dfa *dfa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81378fe0)
Location: security/apparmor/match.c:195
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_dfa_unpack
```
**Symbols:**

```
ffffffff81378fe0-ffffffff81379027: dfa_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dfa_free(struct aa_dfa *dfa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff813b1d80)
Location: security/apparmor/match.c:199
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_teardown_dfa_engine
```
**Symbols:**

```
ffffffff813b1d80-ffffffff813b1dc7: dfa_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dfa_free(struct aa_dfa *dfa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff813c8f40)
Location: security/apparmor/match.c:199
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_teardown_dfa_engine
```
**Symbols:**

```
ffffffff813c8f40-ffffffff813c8f87: dfa_free (STB_LOCAL)
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
In security/apparmor/match.c (ffffffff813de6cd)
Location: security/apparmor/match.c:199
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
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
In security/apparmor/match.c (ffffffff8140505d)
Location: security/apparmor/match.c:199
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
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
In security/apparmor/match.c (ffffffff8143614d)
Location: security/apparmor/match.c:250
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
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
In security/apparmor/match.c (ffffffff81452d6d)
Location: security/apparmor/match.c:250
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/match.c:aa_dfa_free_kref
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
In security/apparmor/match.c (ffffffff8148071c)
Location: security/apparmor/match.c:246
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/match.c:aa_dfa_free_kref
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
In security/apparmor/match.c (ffffffff8149a41c)
Location: security/apparmor/match.c:261
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/match.c:aa_dfa_free_kref
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
In security/apparmor/match.c (ffffffff814f2ed0)
Location: security/apparmor/match.c:271
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
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
In security/apparmor/match.c (ffffffff815100a0)
Location: security/apparmor/match.c:271
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
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
In security/apparmor/match.c (ffffffff81516933)
Location: security/apparmor/match.c:271
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
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
In security/apparmor/match.c (ffffffff81574933)
Location: security/apparmor/match.c:271
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
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
In security/apparmor/match.c (ffffffff81612408)
Location: security/apparmor/match.c:271
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
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
In security/apparmor/match.c (ffffffff816c50b8)
Location: security/apparmor/match.c:271
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
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
In security/apparmor/match.c (ffffffff816fdafc)
Location: security/apparmor/match.c:227
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/match.c:aa_dfa_free_kref
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
In security/apparmor/match.c (ffffffff8173b08b)
Location: security/apparmor/match.c:227
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/match.c:aa_dfa_free_kref
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
In security/apparmor/match.c (ffff800010590694)
Location: security/apparmor/match.c:261
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/match.c:aa_dfa_free_kref
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
In security/apparmor/match.c (c0741210)
Location: security/apparmor/match.c:261
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/match.c:aa_dfa_free_kref
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
In security/apparmor/match.c (c000000000703b64)
Location: security/apparmor/match.c:261
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/match.c:aa_dfa_free_kref
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
In security/apparmor/match.c (ffffffe0003de1aa)
Location: security/apparmor/match.c:261
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/match.c:aa_dfa_free_kref
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
In security/apparmor/match.c (ffffffff814929fc)
Location: security/apparmor/match.c:261
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/match.c:aa_dfa_free_kref
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
In security/apparmor/match.c (ffffffff8148341c)
Location: security/apparmor/match.c:261
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/match.c:aa_dfa_free_kref
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
In security/apparmor/match.c (ffffffff8148ea9c)
Location: security/apparmor/match.c:261
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/match.c:aa_dfa_free_kref
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
In security/apparmor/match.c (ffffffff814a69ac)
Location: security/apparmor/match.c:261
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_unpack
  - security/apparmor/match.c:aa_dfa_free_kref
  - security/apparmor/match.c:aa_dfa_free_kref
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
</ul>
