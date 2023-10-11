<h1>137MHz Weather Satellite Operational Status</h1>
<br>
<p>This page contains the status and some information about weather satellites that transmit on the 137MHz band</p>
<p>Inspired by happysat's <a href=https://github.com/happysat/Meteor-M-N-2-3-Satellite-Operational-Status>Meteor Satellite Operational Status</a> on github</p>
<p>Push mirrored to <a href=https://github.com/thomasdouwes/137MHz-Weather-Satellite-Status>github.com</a> from <a href=https://forgejo.douwes.co.uk/thomas/137MHz-Weather-Satellite-Status>forgejo.douwes.co.uk</a>
<h2>Disclamer:</h2>
<p>I am not an expert! I have tried to make this document as accurate as possible but there may still be inaccuracies, I have cited sources where possible. If you think I have made an error please open an issue on the github repo with what I have done wrong</p>
<h2>Satellites:</h2>
<br>
<!--Meteor-M N2-3-->
<details open="true">
    <summary>Meteor-M N2-3</summary>
    <table class="wxstatus">
        <tbody>
            <tr><td>
            <h2>Meteor-M N2-3:</h2>
            <h3>Downlinks:</h3>
            <details open="true">
                <summary>LRPT (Low Rate Picture Transmission)</summary>
                <table class="wxstatus">
                <tr><td>
                <table>
                    <thead>
                        <tr>
                            <td><h4>Frequency</h4></td>
                            <td><h4>Modulation</h4></td>
                            <td><h4>SymbolRate</h4></td>
                            <td><h4>Status</h4></td>
                        </tr>
                        <tr>
                            <td>137.900MHz</td>
                            <td>OQPSK</td>
                            <td>72.000K</td>
                            <td>On</td>
                        </tr>
                    </thead>
                </table>
                <h2>Notes:</h2>
                Current data:<br>
                MSU-MR channels 1, 2, 4
                </table>
            </details>
            <h2>Instruments:</h2>  
            <details>
                <summary>MSU-MR (VIS/IR Imaging Radiometer)</summary>
                <table class="wxstatus">
                <tr><td>
                <table>
                    <thead>
                        <tr>
                            <td><h4>Status</h4></td>
                        </tr>
                        <tr>
                            <td>Ok</td>
                        </tr>
                    </thead>
                </table>
                Channels light wavelenghts:<br>
                <br>
                Channel 1 Visible Green-Red  (0.50 - 0.70 µm)<br>
                Channel 2 Near IR   (0.70 - 1.10 µm)<br>
                Channel 3 Near IR   (1.60 - 1.80 µm)<br>
                Channel 4 Mid IR    (3.50 - 4.10 µm)<br>
                Channel 5 Far IR    (10.5 - 11.5 µm)<br>
                Channel 6 Far IR    (11.5 - 12.5 µm)<br>
                <br>
                From <a href=https://space.oscar.wmo.int/instruments/view/msu_mr>space.oscar.wmo.int</a>
                <h2>Notes:</h2>
                </table>
            </details>
            <h2>Notes:</h2>
            <h2>Log:</h2>
            <h3>2023-10-6</h3>
            Switched channels to 124 from 123
            <h3>2023-09-05</h3>
            Meteor-M 2-3 is having orientation issues
        </tbody>
    </table>
</details>

<!--NOAA 19-->
<details open="true">
    <summary>NOAA 19</summary>
    <table class="wxstatus">
        <tbody>
            <tr><td>
            <h2>NOAA 19:</h2>
            <h3>Downlinks:</h3>
            <details open="true">
                <summary>APT (Automatic Picture Transmission)</summary>
                <table class="wxstatus">
                <tr><td>
                <table>
                    <thead>
                        <tr>
                            <td><h4>Frequency</h4></td>
                            <td><h4>Modulation</h4></td>
                            <td><h4>SymbolRate</h4></td>
                            <td><h4>Status</h4></td>
                        </tr>
                        <tr>
                            <td>137.100MHz</td>
                            <td>Analog</td>
                            <td>N/A</td>
                            <td>On</td>
                        </tr>
                    </thead>
                </table>
                <h2>Notes:</h2>
                APT Channel A: AVHRR channel 2<br>
                APT Channel B: AVHRRR channel 4<br>
                </table>
            </details>
            <details open="true">
                <summary>DSB (Direct Sounder Broadcast)</summary>
                <table class="wxstatus">
                <tr><td>
                <table>
                    <thead>
                        <tr>
                            <td><h4>Frequency</h4></td>
                            <td><h4>Modulation</h4></td>
                            <td><h4>SymbolRate</h4></td>
                            <td><h4>Status</h4></td>
                        </tr>
                        <tr>
                            <td>137.770MHz</td>
                            <td>BPSK</td>
                            <td>TODO</td>
                            <td>On</td>
                        </tr>
                    </thead>
                </table>
                <h2>Notes:</h2>
                All HIRS and SEM channels + some satellite telemetry
                </table>
            </details>
            <h2>Instruments:</h2>
            <details>
                <summary>AVHRR/3 (Advanced very-high-resolution radiometer)</summary>
                <table class="wxstatus">
                <tr><td>
                <table>
                    <thead>
                        <tr>
                            <td><h4>Status</h4></td>
                        </tr>
                        <tr>
                            <td>Ok</td>
                        </tr>
                    </thead>
                </table>
                Channels light wavelenghts:<br>
                <br>
                Channel 1 Visible Green-Red  (0.58 - 0.68 µm)<br>
                Channel 2 Near IR   (0.725  - 1.00 µm)<br>
                Channel 3 Near IR   (1.58 - 1.64 µm)<br>
                Channel 4 Mid IR    (3.55 - 3.93 µm)<br>
                Channel 5 Far IR    (10.3 - 11.3 µm)<br>
                Channel 6 Far IR    (11.5 - 12.5 µm)<br>
                <br>
                From <a href=https://space.oscar.wmo.int/instruments/view/avhrr_3>space.oscar.wmo.int</a>
                <h2>Notes:</h2>
                </table>
            </details>
            <details>
                <summary>HIRS/4 (High resolution Infrared Radiation Sounder)</summary>
                <table class="wxstatus">
                <tr><td>
                <table>
                    <thead>
                        <tr>
                            <td><h4>Status</h4></td>
                        </tr>
                        <tr>
                            <td>Ok</td>
                        </tr>
                    </thead>
                </table>
                Channels light wavelenghts:<br>
                <br>
                Channel 1 Far IR  (14.95 µm)<br>
                Channel 2 Far IR  (14.71 µm)<br>
                Channel 3 Far IR  (14.49 µm)<br>
                Channel 4 Far IR  (14.22 µm)<br>
                Channel 5 Far IR  (13.97 µm)<br>
                Channel 6 Far IR  (13.64 µm)<br>
                Channel 7 Far IR  (13.35 µm)<br>
                Channel 8 Far IR  (12.47 µm)<br>
                Channel 9 Far IR  (11.11 µm)<br>
                Channel 10 Far IR  (9.71 µm)<br>
                Channel 11 Far IR  (7.33 µm)<br>
                Channel 12 Far IR  (6.52 µm)<br>
                Channel 13 Mid IR  (4.57 µm)<br>
                Channel 14 Mid IR  (4.52 µm)<br>
                Channel 15 Mid IR  (4.47 µm)<br>
                Channel 16 Mid IR  (4.45 µm)<br>
                Channel 17 Mid IR  (4.13 µm)<br>
                Channel 18 Mid IR  (4.00 µm)<br>
                Channel 19 Mid IR  (3.76 µm)<br>
                Channel 20 Visible Red  (0.69 µm)<br>
                <br>
                From <a href=https://space.oscar.wmo.int/instruments/view/hirs_4>space.oscar.wmo.int</a>
                <h2>Notes:</h2>
                </table>
            </details>
            <details>
                <summary>SEM</summary>
                <table class="wxstatus">
                <tr><td>
                <table>
                    <thead>
                        <tr>
                            <td><h4>Status</h4></td>
                        </tr>
                        <tr>
                            <td>Ok</td>
                        </tr>
                    </thead>
                </table>
                I can't be bothered to do this one<br>
                see <a href=https://space.oscar.wmo.int/instruments/view/sem_meped>SEM/MEPED</a> and <a href=https://space.oscar.wmo.int/instruments/view/sem_ted>SEM/TED</a>
                <h2>Notes:</h2>
                </table>
            </details>
            <h2>Notes:</h2>
            <h2>Log:</h2>
            Nothing yet
        </tbody>
    </table>
</details>

<!--NOAA 18-->
<details open="true">
    <summary>NOAA 18</summary>
    <table class="wxstatus">
        <tbody>
            <tr><td>
            <h2>NOAA 18:</h2>
            <h3>Downlinks:</h3>
            <details open="true">
                <summary>APT (Automatic Picture Transmission)</summary>
                <table class="wxstatus">
                <tr><td>
                <table>
                    <thead>
                        <tr>
                            <td><h4>Frequency</h4></td>
                            <td><h4>Modulation</h4></td>
                            <td><h4>SymbolRate</h4></td>
                            <td><h4>Status</h4></td>
                        </tr>
                        <tr>
                            <td>137.9125MHz</td>
                            <td>Analog</td>
                            <td>N/A</td>
                            <td>On</td>
                        </tr>
                    </thead>
                </table>
                <h2>Notes:</h2>
                APT Channel A: AVHRR channel 1<br>
                APT Channel B: AVHRRR channel 4<br>
                </table>
            </details>
            <details open="true">
                <summary>DSB (Direct Sounder Broadcast)</summary>
                <table class="wxstatus">
                <tr><td>
                <table>
                    <thead>
                        <tr>
                            <td><h4>Frequency</h4></td>
                            <td><h4>Modulation</h4></td>
                            <td><h4>SymbolRate</h4></td>
                            <td><h4>Status</h4></td>
                        </tr>
                        <tr>
                            <td>137.350MHz</td>
                            <td>BPSK</td>
                            <td>TODO</td>
                            <td>On</td>
                        </tr>
                    </thead>
                </table>
                <h2>Notes:</h2>
                All HIRS and SEM channels + some satellite telemetry
                </table>
            </details>
            <h2>Instruments:</h2>
            <details>
                <summary>AVHRR/3 (Advanced very-high-resolution radiometer)</summary>
                <table class="wxstatus">
                <tr><td>
                <table>
                    <thead>
                        <tr>
                            <td><h4>Status</h4></td>
                        </tr>
                        <tr>
                            <td>Ok</td>
                        </tr>
                    </thead>
                </table>
                Channels light wavelenghts:<br>
                <br>
                Channel 1 Visible Green-Red  (0.58 - 0.68 µm)<br>
                Channel 2 Near IR   (0.725  - 1.00 µm)<br>
                Channel 3 Near IR   (1.58 - 1.64 µm)<br>
                Channel 4 Mid IR    (3.55 - 3.93 µm)<br>
                Channel 5 Far IR    (10.3 - 11.3 µm)<br>
                Channel 6 Far IR    (11.5 - 12.5 µm)<br>
                <br>
                From <a href=https://space.oscar.wmo.int/instruments/view/avhrr_3>space.oscar.wmo.int</a>
                <h2>Notes:</h2>
                </table>
            </details>
            <details>
                <summary>HIRS/4 (High resolution Infrared Radiation Sounder)</summary>
                <table class="wxstatus">
                <tr><td>
                <table>
                    <thead>
                        <tr>
                            <td><h4>Status</h4></td>
                        </tr>
                        <tr>
                            <td>Ok</td>
                        </tr>
                    </thead>
                </table>
                Channels light wavelenghts:<br>
                <br>
                Channel 1 Far IR  (14.95 µm)<br>
                Channel 2 Far IR  (14.71 µm)<br>
                Channel 3 Far IR  (14.49 µm)<br>
                Channel 4 Far IR  (14.22 µm)<br>
                Channel 5 Far IR  (13.97 µm)<br>
                Channel 6 Far IR  (13.64 µm)<br>
                Channel 7 Far IR  (13.35 µm)<br>
                Channel 8 Far IR  (12.47 µm)<br>
                Channel 9 Far IR  (11.11 µm)<br>
                Channel 10 Far IR  (9.71 µm)<br>
                Channel 11 Far IR  (7.33 µm)<br>
                Channel 12 Far IR  (6.52 µm)<br>
                Channel 13 Mid IR  (4.57 µm)<br>
                Channel 14 Mid IR  (4.52 µm)<br>
                Channel 15 Mid IR  (4.47 µm)<br>
                Channel 16 Mid IR  (4.45 µm)<br>
                Channel 17 Mid IR  (4.13 µm)<br>
                Channel 18 Mid IR  (4.00 µm)<br>
                Channel 19 Mid IR  (3.76 µm)<br>
                Channel 20 Visible Red  (0.69 µm)<br>
                <br>
                From <a href=https://space.oscar.wmo.int/instruments/view/hirs_4>space.oscar.wmo.int</a>
                <h2>Notes:</h2>
                </table>
            </details>
            <details>
                <summary>SEM</summary>
                <table class="wxstatus">
                <tr><td>
                I can't be bothered to do this one<br>
                see <a href=https://space.oscar.wmo.int/instruments/view/sem_meped>SEM/MEPED</a> and <a href=https://space.oscar.wmo.int/instruments/view/sem_ted>SEM/TED</a>
                <h2>Notes:</h2>
                </table>
            </details>
            <h2>Notes:</h2>
            NOAA 18 is the only POES satellites that uses AVHRR channel 1 (visible) on APT<br>
            The DSB on NOAA 18 sometimes temporarly switches off, I'm not sure why this happens<br>
            <h2>Log:</h2>
            <h3>2023-08-28</h3>
            NOAA seems to be doing something with the APT channels, they switched seem to have AVHRR channel 1 (visible) at night causing a black image<br>
        </tbody>
    </table>
</details>

<!--NOAA 15-->
<details open="true">
    <summary>NOAA 15</summary>
    <table class="wxstatus">
        <tbody>
            <tr><td>
            <h2>NOAA 15:</h2>
            <h3>Downlinks:</h3>
            <details open="true">
                <summary>APT (Automatic Picture Transmission)</summary>
                <table class="wxstatus">
                <tr><td>
                <table>
                    <thead>
                        <tr>
                            <td><h4>Frequency</h4></td>
                            <td><h4>Modulation</h4></td>
                            <td><h4>SymbolRate</h4></td>
                            <td><h4>Status</h4></td>
                        </tr>
                        <tr>
                            <td>137.620MHz</td>
                            <td>Analog</td>
                            <td>N/A</td>
                            <td>On</td>
                        </tr>
                    </thead>
                </table>
                <h2>Notes:</h2>
                APT Channel A: AVHRR channel 2<br>
                APT Channel B: AVHRRR channel 4<br>
                </table>
            </details>
            <details open="true">
                <summary>DSB (Direct Sounder Broadcast)</summary>
                <table class="wxstatus">
                <tr><td>
                <table>
                    <thead>
                        <tr>
                            <td><h4>Frequency</h4></td>
                            <td><h4>Modulation</h4></td>
                            <td><h4>SymbolRate</h4></td>
                            <td><h4>Status</h4></td>
                        </tr>
                        <tr>
                            <td>137.350MHz</td>
                            <td>BPSK</td>
                            <td>TODO</td>
                            <td>On</td>
                        </tr>
                    </thead>
                </table>
                <h2>Notes:</h2>
                All HIRS and SEM channels + some satellite telemetry
                </table>
            </details>
            <h2>Instruments:</h2>
            <details>
                <summary>AVHRR/3 (Advanced very-high-resolution radiometer)</summary>
                <table class="wxstatus">
                <tr><td>
                <table>
                    <thead>
                        <tr>
                            <td><h4>Status</h4></td>
                        </tr>
                        <tr>
                            <td>Degraded</td>
                        </tr>
                    </thead>
                </table>
                Channels light wavelenghts:<br>
                <br>
                Channel 1 Visible Green-Red  (0.58 - 0.68 µm)<br>
                Channel 2 Near IR   (0.725  - 1.00 µm)<br>
                Channel 3 Near IR   (1.58 - 1.64 µm)<br>
                Channel 4 Mid IR    (3.55 - 3.93 µm)<br>
                Channel 5 Far IR    (10.3 - 11.3 µm)<br>
                Channel 6 Far IR    (11.5 - 12.5 µm)<br>
                <br>
                From <a href=https://space.oscar.wmo.int/instruments/view/avhrr_3>space.oscar.wmo.int</a>
                <h2>Notes:</h2>
                </table>
            </details>
            <details>
                <summary>HIRS/3 (High resolution Infrared Radiation Sounder)</summary>
                <table class="wxstatus">
                <tr><td>
                <table>
                    <thead>
                        <tr>
                            <td><h4>Status</h4></td>
                        </tr>
                        <tr>
                            <td>Ok</td>
                        </tr>
                    </thead>
                </table>
                Channels light wavelenghts:<br>
                <br>
                Channel 1 Far IR  (14.95 µm)<br>
                Channel 2 Far IR  (14.71 µm)<br>
                Channel 3 Far IR  (14.49 µm)<br>
                Channel 4 Far IR  (14.22 µm)<br>
                Channel 5 Far IR  (13.97 µm)<br>
                Channel 6 Far IR  (13.64 µm)<br>
                Channel 7 Far IR  (13.35 µm)<br>
                Channel 8 Far IR  (12.47 µm)<br>
                Channel 9 Far IR  (11.11 µm)<br>
                Channel 10 Far IR  (9.71 µm)<br>
                Channel 11 Far IR  (7.33 µm)<br>
                Channel 12 Far IR  (6.52 µm)<br>
                Channel 13 Mid IR  (4.57 µm)<br>
                Channel 14 Mid IR  (4.52 µm)<br>
                Channel 15 Mid IR  (4.47 µm)<br>
                Channel 16 Mid IR  (4.45 µm)<br>
                Channel 17 Mid IR  (4.13 µm)<br>
                Channel 18 Mid IR  (4.00 µm)<br>
                Channel 19 Mid IR  (3.76 µm)<br>
                Channel 20 Visible Red  (0.69 µm)<br>
                <br>
                From <a href=https://space.oscar.wmo.int/instruments/view/hirs_4>space.oscar.wmo.int</a>
                <h2>Notes:</h2>
                </table>
            </details>
            <details>
                <summary>SEM</summary>
                <table class="wxstatus">
                <tr><td>
                <table>
                    <thead>
                        <tr>
                            <td><h4>Status</h4></td>
                        </tr>
                        <tr>
                            <td>Ok</td>
                        </tr>
                    </thead>
                </table>
                I can't be bothered to do this one<br>
                see <a href=https://space.oscar.wmo.int/instruments/view/sem_meped>SEM/MEPED</a> and <a href=https://space.oscar.wmo.int/instruments/view/sem_ted>SEM/TED</a>
                <h2>Notes:</h2>
                </table>
            </details>
            <h2>Notes:</h2>
            NOAA 15 is the only active POES satellites that has the older HIRS/3 instead of HIRS/4<br>
            <h2>Log:</h2>
            <h3>2023-08-28</h3>
            The AVHRR scan motor appears to be stuck, corrupting the main image data. The MIRP (onboard computer) does not seem capable of using this data and makes an unsyncable APT signal<br>
        </tbody>
    </table>
</details>
