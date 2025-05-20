# Function: <code>set_machine_trusted_keys</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void set_machine_trusted_keys(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff834899d3)
Location: certs/system_keyring.c:100
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_init_keyring
```
**Symbols:**

```
ffffffff834899d3-ffffffff83489a0e: set_machine_trusted_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void set_machine_trusted_keys(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff83eba100)
Location: certs/system_keyring.c:100
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_init_keyring
```
**Symbols:**

```
ffffffff83eba100-ffffffff83eba13b: set_machine_trusted_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void set_machine_trusted_keys(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff836df750)
Location: certs/system_keyring.c:108
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_init_keyring
```
**Symbols:**

```
ffffffff836df750-ffffffff836df78b: set_machine_trusted_keys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void set_machine_trusted_keys(struct key *keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff83911f90)
Location: certs/system_keyring.c:187
Inline: False
Direct callers:
  - security/integrity/digsig.c:integrity_init_keyring
```
**Symbols:**

```
ffffffff83911f90-ffffffff83911fcb: set_machine_trusted_keys (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
