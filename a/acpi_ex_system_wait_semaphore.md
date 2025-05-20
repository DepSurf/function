# Function: <code>acpi_ex_system_wait_semaphore</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void *semaphore, u16 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exsystem.c (ffffffff81499d0b)
Location: drivers/acpi/acpica/exsystem.c:65
Inline: True
Direct callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event
```
**Symbols:**

```
ffffffff81499d0b-ffffffff81499d58: acpi_ex_system_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void *semaphore, u16 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exsystem.c (ffffffff814e8a5a)
Location: drivers/acpi/acpica/exsystem.c:65
Inline: True
Direct callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event
```
**Symbols:**

```
ffffffff814e8a5a-ffffffff814e8aa7: acpi_ex_system_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void *semaphore, u16 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exsystem.c (ffffffff8150b2ae)
Location: drivers/acpi/acpica/exsystem.c:65
Inline: True
Direct callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event
```
**Symbols:**

```
ffffffff8150b2ae-ffffffff8150b2fb: acpi_ex_system_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void *semaphore, u16 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exsystem.c (ffffffff8151b8de)
Location: drivers/acpi/acpica/exsystem.c:65
Inline: True
Direct callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event
```
**Symbols:**

```
ffffffff8151b8de-ffffffff8151b92b: acpi_ex_system_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void *semaphore, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exsystem.c (ffffffff8156b388)
Location: drivers/acpi/acpica/exsystem.c:65
Inline: False
Direct callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event
```
**Symbols:**

```
ffffffff8156b388-ffffffff8156b482: acpi_ex_system_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void *semaphore, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exsystem.c (ffffffff815a1fe0)
Location: drivers/acpi/acpica/exsystem.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event
```
**Symbols:**

```
ffffffff815a1fe0-ffffffff815a20da: acpi_ex_system_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void *semaphore, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exsystem.c (ffffffff815baca0)
Location: drivers/acpi/acpica/exsystem.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event
```
**Symbols:**

```
ffffffff815baca0-ffffffff815bad9a: acpi_ex_system_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void *semaphore, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exsystem.c (ffffffff815ec872)
Location: drivers/acpi/acpica/exsystem.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event
```
**Symbols:**

```
ffffffff815ec872-ffffffff815ec96d: acpi_ex_system_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void *semaphore, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exsystem.c (ffffffff8160dc07)
Location: drivers/acpi/acpica/exsystem.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event
```
**Symbols:**

```
ffffffff8160dc07-ffffffff8160dd02: acpi_ex_system_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void *semaphore, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exsystem.c (ffffffff816b9f65)
Location: drivers/acpi/acpica/exsystem.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event
```
**Symbols:**

```
ffffffff816b9f65-ffffffff816ba060: acpi_ex_system_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void *semaphore, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exsystem.c (ffffffff816d795d)
Location: drivers/acpi/acpica/exsystem.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event
```
**Symbols:**

```
ffffffff816d795d-ffffffff816d7a58: acpi_ex_system_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void *semaphore, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exsystem.c (ffffffff816b98f2)
Location: drivers/acpi/acpica/exsystem.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event
```
**Symbols:**

```
ffffffff816b98f2-ffffffff816b99ed: acpi_ex_system_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void *semaphore, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exsystem.c (ffffffff81730942)
Location: drivers/acpi/acpica/exsystem.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event
```
**Symbols:**

```
ffffffff81730942-ffffffff81730a3d: acpi_ex_system_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void *semaphore, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exsystem.c (ffffffff81861484)
Location: drivers/acpi/acpica/exsystem.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event
```
**Symbols:**

```
ffffffff81861484-ffffffff81861590: acpi_ex_system_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void *semaphore, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exsystem.c (ffffffff8199e5b0)
Location: drivers/acpi/acpica/exsystem.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event
```
**Symbols:**

```
ffffffff8199e5b0-ffffffff8199e6e2: acpi_ex_system_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void *semaphore, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exsystem.c (ffffffff819e5280)
Location: drivers/acpi/acpica/exsystem.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event
```
**Symbols:**

```
ffffffff819e5280-ffffffff819e53b2: acpi_ex_system_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void *semaphore, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exsystem.c (ffffffff81a2ffd0)
Location: drivers/acpi/acpica/exsystem.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event
```
**Symbols:**

```
ffffffff81a2ffd0-ffffffff81a30102: acpi_ex_system_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void *semaphore, u16 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exsystem.c (ffff80001078a1ac)
Location: drivers/acpi/acpica/exsystem.c:31
Inline: True
Direct callers:
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event
```
**Symbols:**

```
ffff80001078a1ac-ffff80001078a21c: acpi_ex_system_wait_semaphore (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void *semaphore, u16 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exsystem.c (ffffffff815efc3c)
Location: drivers/acpi/acpica/exsystem.c:31
Inline: True
Direct callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event
```
**Symbols:**

```
ffffffff815efc3c-ffffffff815efc89: acpi_ex_system_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void *semaphore, u16 timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exsystem.c (ffffffff815db213)
Location: drivers/acpi/acpica/exsystem.c:31
Inline: True
Direct callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event
```
**Symbols:**

```
ffffffff815db213-ffffffff815db260: acpi_ex_system_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void *semaphore, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exsystem.c (ffffffff81601ee7)
Location: drivers/acpi/acpica/exsystem.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event
```
**Symbols:**

```
ffffffff81601ee7-ffffffff81601fe2: acpi_ex_system_wait_semaphore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_ex_system_wait_semaphore(void *semaphore, u16 timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exsystem.c (ffffffff8161bd97)
Location: drivers/acpi/acpica/exsystem.c:31
Inline: False
Direct callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_acquire_global_lock
  - drivers/acpi/acpica/exsystem.c:acpi_ex_system_wait_event
```
**Symbols:**

```
ffffffff8161bd97-ffffffff8161be92: acpi_ex_system_wait_semaphore (STB_GLOBAL)
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
