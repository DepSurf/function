# Function: <code>crb_try_pluton_doorbell</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crb_try_pluton_doorbell(struct crb_priv *priv, bool wait_for_complete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff81afc570)
Location: drivers/char/tpm/tpm_crb.c:137
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_cmd_ready
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
```
**Symbols:**

```
ffffffff81afc570-ffffffff81afc5ea: crb_try_pluton_doorbell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crb_try_pluton_doorbell(struct crb_priv *priv, bool wait_for_complete);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff81b4fb80)
Location: drivers/char/tpm/tpm_crb.c:137
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_cmd_ready
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
```
**Symbols:**

```
ffffffff81b4fb80-ffffffff81b4fbfa: crb_try_pluton_doorbell (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
