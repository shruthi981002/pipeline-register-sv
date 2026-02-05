Single-Stage Pipeline Register (SystemVerilog)

This repository contains a clean and fully synthesizable implementation of single-stage pipeline register using a standard valid/ready handshake. The design focuses on correctness, simplicity, and proper handling of backpressure between upstream and downstream interfaces.

->Safely handles backpressure without data loss
->Guarantees no data duplication
->Resets to a clean, empty state

Interface Overview
Input interface: in_valid, in_ready, in_data
Output interface: out_valid, out_ready, out_data
