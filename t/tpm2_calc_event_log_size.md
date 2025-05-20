# Function: <code>tpm2_calc_event_log_size</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/tpm.c (ffffffff8290e1a6)
Location: drivers/firmware/efi/tpm.c:19
Inline: True
Inline callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
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
In drivers/firmware/efi/tpm.c (ffffffff82917b99)
Location: drivers/firmware/efi/tpm.c:19
Inline: True
Inline callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
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
In drivers/firmware/efi/tpm.c (ffffffff82d2a168)
Location: drivers/firmware/efi/tpm.c:19
Inline: True
Inline callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
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
In drivers/firmware/efi/tpm.c (ffffffff8301888d)
Location: drivers/firmware/efi/tpm.c:19
Inline: True
Inline callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
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
In drivers/firmware/efi/tpm.c (ffffffff8322387a)
Location: drivers/firmware/efi/tpm.c:19
Inline: True
Inline callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
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
In drivers/firmware/efi/tpm.c (ffffffff8330d680)
Location: drivers/firmware/efi/tpm.c:19
Inline: True
Inline callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tpm2_calc_event_log_size(void *data, int count, void *size_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/tpm.c (ffffffff834c7087)
Location: drivers/firmware/efi/tpm.c:19
Inline: False
Direct callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
**Symbols:**

```
ffffffff834c7087-ffffffff834c72c9: tpm2_calc_event_log_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm2_calc_event_log_size(void *data, int count, void *size_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/tpm.c (ffffffff83f083c0)
Location: drivers/firmware/efi/tpm.c:19
Inline: False
Direct callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
**Symbols:**

```
ffffffff83f083c0-ffffffff83f08653: tpm2_calc_event_log_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm2_calc_event_log_size(void *data, int count, void *size_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/tpm.c (ffffffff8372e500)
Location: drivers/firmware/efi/tpm.c:19
Inline: False
Direct callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
**Symbols:**

```
ffffffff8372e500-ffffffff8372e792: tpm2_calc_event_log_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm2_calc_event_log_size(void *data, int count, void *size_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/tpm.c (ffffffff83962900)
Location: drivers/firmware/efi/tpm.c:19
Inline: False
Direct callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
**Symbols:**

```
ffffffff83962900-ffffffff83962b92: tpm2_calc_event_log_size (STB_LOCAL)
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
In drivers/firmware/efi/tpm.c (ffff8000114a6490)
Location: drivers/firmware/efi/tpm.c:19
Inline: True
Inline callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
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
In drivers/firmware/efi/tpm.c (c15a8858)
Location: drivers/firmware/efi/tpm.c:19
Inline: True
Inline callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/tpm.c (ffffffff828fcf9f)
Location: drivers/firmware/efi/tpm.c:19
Inline: True
Inline callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
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
In drivers/firmware/efi/tpm.c (ffffffff828f483b)
Location: drivers/firmware/efi/tpm.c:19
Inline: True
Inline callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
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
In drivers/firmware/efi/tpm.c (ffffffff829121ce)
Location: drivers/firmware/efi/tpm.c:19
Inline: True
Inline callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
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
In drivers/firmware/efi/tpm.c (ffffffff82918bfb)
Location: drivers/firmware/efi/tpm.c:19
Inline: True
Inline callers:
  - drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init
```
</details>
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
