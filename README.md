# esp32_simple_snmpv2c_agent
IoT: Simple example using SNMPv2c Agent for ESP32 + LwIP 2.0.3 + ESP-IDF 3.0

/**
 * @file
 * Simple SNMPv2c Agent Example for ESP32 by Leandro Silva
 * Tested on... 
 * Board: ESP32_Core_board_V2
 * Version: Framework ESP-IDF 3.0
 * Version: LWIP 2.0.3
 *
 */
 
/*
 * Copyright (c) July 2018 Leandro Silva <@gmail.com>
 * Student of Computer Engineering from Polytechnic Institute of Leiria - Portugal
 * 
 * Redistribution and use in source and binary forms, with or without modification, 
 * are permitted provided that the following conditions are met:
 *
 * 1. Redistributions of source code must retain the above copyright notice,
 *    this list of conditions and the following disclaimer.
 * 2. Redistributions in binary form must reproduce the above copyright notice,
 *    this list of conditions and the following disclaimer in the documentation
 *    and/or other materials provided with the distribution.
 * 3. The name of the author may not be used to endorse or promote products
 *    derived from this software without specific prior written permission. 
 *
 * THIS SOFTWARE IS PROVIDED BY THE AUTHOR ``AS IS'' AND ANY EXPRESS OR IMPLIED 
 * WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF 
 * MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT 
 * SHALL THE AUTHOR BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, 
 * EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT 
 * OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS 
 * INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN 
 * CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING 
 * IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY 
 * OF SUCH DAMAGE.
 *
 * This is an simple example of SNMPv2c Agent w/ private MIB for ESP32.
 * 
 * Author: Leandro Silva <@gmail.com>
 * Student of Computer Engineering from Polytechnic Institute of Leiria - Portugal
 *
 * Please be kind and support my work for further release, any donation is apreciated
 * at https://www.paypal.me/LeandroAdonis/5 for 5€ or 5$ amount. Any amount you wish, 
 * I will be very gratefull and real happy to see my work worth something to you. Thank you.
 *
 */
