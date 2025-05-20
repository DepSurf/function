# Function: <code>ktime_get_seconds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
time64_t ktime_get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f4860)
Location: kernel/time/timekeeping.c:827
Inline: False
```
**Symbols:**

```
ffffffff810f4860-ffffffff810f4895: ktime_get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
time64_t ktime_get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fb980)
Location: kernel/time/timekeeping.c:832
Inline: False
Direct callers:
  - kernel/cpuset.c:fmeter_update
```
**Symbols:**

```
ffffffff810fb980-ffffffff810fb9b5: ktime_get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
time64_t ktime_get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fe880)
Location: kernel/time/timekeeping.c:861
Inline: False
Direct callers:
  - kernel/cpuset.c:fmeter_update
```
**Symbols:**

```
ffffffff810fe880-ffffffff810fe8b5: ktime_get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
time64_t ktime_get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81100b10)
Location: kernel/time/timekeeping.c:893
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:fmeter_update
```
**Symbols:**

```
ffffffff81100b10-ffffffff81100b37: ktime_get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
time64_t ktime_get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110b910)
Location: kernel/time/timekeeping.c:897
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:fmeter_update
```
**Symbols:**

```
ffffffff8110b910-ffffffff8110b936: ktime_get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
time64_t ktime_get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811170d0)
Location: kernel/time/timekeeping.c:898
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:fmeter_update
```
**Symbols:**

```
ffffffff811170d0-ffffffff811170f6: ktime_get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
time64_t ktime_get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81122710)
Location: kernel/time/timekeeping.c:905
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:fmeter_update
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
**Symbols:**

```
ffffffff81122710-ffffffff81122736: ktime_get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
time64_t ktime_get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:912
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:fmeter_update
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
**Symbols:**

```
ffffffff8112f769-ffffffff8112f77c: ktime_get_seconds.cold (STB_LOCAL)
ffffffff8112d510-ffffffff8112d530: ktime_get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
time64_t ktime_get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811393b0)
Location: kernel/time/timekeeping.c:912
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:fmeter_update
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
**Symbols:**

```
ffffffff811393b0-ffffffff811393d7: ktime_get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
time64_t ktime_get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81148060)
Location: kernel/time/timekeeping.c:912
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:fmeter_update
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
**Symbols:**

```
ffffffff81148060-ffffffff81148087: ktime_get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
time64_t ktime_get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811444a0)
Location: kernel/time/timekeeping.c:982
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:fmeter_update
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
**Symbols:**

```
ffffffff811444a0-ffffffff811444c7: ktime_get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
time64_t ktime_get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81145620)
Location: kernel/time/timekeeping.c:982
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:fmeter_update
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
**Symbols:**

```
ffffffff81145620-ffffffff81145647: ktime_get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
time64_t ktime_get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81168d20)
Location: kernel/time/timekeeping.c:982
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:fmeter_update
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
**Symbols:**

```
ffffffff81168d20-ffffffff81168d47: ktime_get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
time64_t ktime_get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8119c8b0)
Location: kernel/time/timekeeping.c:1001
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:fmeter_update
  - drivers/char/random.c:crng_make_state
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
**Symbols:**

```
ffffffff8119c8b0-ffffffff8119c8df: ktime_get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
time64_t ktime_get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811db2e0)
Location: kernel/time/timekeeping.c:1001
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:fmeter_update
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:crng_reseed
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
**Symbols:**

```
ffffffff811db2e0-ffffffff811db30f: ktime_get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
time64_t ktime_get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811ef880)
Location: kernel/time/timekeeping.c:1001
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:fmeter_update
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:crng_reseed
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
**Symbols:**

```
ffffffff811ef880-ffffffff811ef8af: ktime_get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
time64_t ktime_get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81205910)
Location: kernel/time/timekeeping.c:1001
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:fmeter_update
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:crng_reseed
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
**Symbols:**

```
ffffffff81205910-ffffffff8120593f: ktime_get_seconds (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
time64_t ktime_get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a3160)
Location: kernel/time/timekeeping.c:912
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:fmeter_update
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
**Symbols:**

```
ffff8000101a3160-ffff8000101a31a0: ktime_get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
time64_t ktime_get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c03ed1f0)
Location: kernel/time/timekeeping.c:912
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:fmeter_update
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
**Symbols:**

```
c03ed1f0-c03ed248: ktime_get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
time64_t ktime_get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c000000000204a30)
Location: kernel/time/timekeeping.c:912
Inline: False
Direct callers:
  - arch/powerpc/kernel/eeh_pe.c:eeh_pe_update_time_stamp
  - arch/powerpc/kernel/eeh_pe.c:eeh_pe_update_time_stamp
  - kernel/cgroup/cpuset.c:fmeter_update
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
**Symbols:**

```
c000000000204a30-c000000000204a64: ktime_get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
time64_t ktime_get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe00012fdaa)
Location: kernel/time/timekeeping.c:912
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:fmeter_update
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
**Symbols:**

```
ffffffe00012fdaa-ffffffe00012fde8: ktime_get_seconds (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
time64_t ktime_get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81131b60)
Location: kernel/time/timekeeping.c:912
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:fmeter_update
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
**Symbols:**

```
ffffffff81131b60-ffffffff81131b87: ktime_get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
time64_t ktime_get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811245c0)
Location: kernel/time/timekeeping.c:912
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:fmeter_update
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
**Symbols:**

```
ffffffff811245c0-ffffffff811245e7: ktime_get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
time64_t ktime_get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112f880)
Location: kernel/time/timekeeping.c:912
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:fmeter_update
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
**Symbols:**

```
ffffffff8112f880-ffffffff8112f8a7: ktime_get_seconds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
time64_t ktime_get_seconds();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113c2a0)
Location: kernel/time/timekeeping.c:912
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:fmeter_update
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_check_req
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
  - net/ipv4/tcp_minisocks.c:tcp_timewait_state_process
```
**Symbols:**

```
ffffffff8113c2a0-ffffffff8113c2c7: ktime_get_seconds (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
