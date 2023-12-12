# Dataset Contribution Guidelines

Thank you for considering contributing to our dataset repository! Please follow the guidelines below to ensure a smooth contribution process.

## Dataset Format

Our dataset follows a specific format with the following columns:

1. `ip.src`
2. `ip.dst`
3. `tcp.srcport`
4. `tcp.dstport`
5. `ip.proto`
6. `frame.len`
7. `tcp.flags.syn`
8. `tcp.flags.reset`
9. `tcp.flags.push`
10. `tcp.flags.ack`
11. `ip.flags.mf`
12. `ip.flags.df`
13. `ip.flags.rb`
14. `tcp.seq`
15. `tcp.ack`
16. `frame.time`
17. `Packets`
18. `Bytes`
19. `Tx Packets`
20. `Tx Bytes`
21. `Rx Packets`
22. `Rx Bytes`
23. `Label`

Ensure that your dataset adheres to this column structure for consistency.

## Contribution Process

1. **Fork the Repository:** Start by forking the repository to your GitHub account.

2. **Clone the Repository:** Clone the forked repository to your local machine.

   ```bash
   git clone https://github.com/<your-username>/YADD.git
