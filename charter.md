There are many situations in which it is desirable to take
measurements of data which people consider sensitive. For instance,
one might want to measure web sites that do not render properly
or exposure to some disease. In these cases, the entity taking the
measurement is not interested in people's individual responses but
rather in aggregated data (e.g., how many users had errors on site X),
Conventional methods require collecting individual measurements and then
aggregating them, thus representing a threat to user privacy and
rendering many such measurements difficult and impractical.

New cryptographic techniques such as Prio address this gap by splitting
measurements between multiple, non-colluding servers which can jointly compute the
aggregate value without either server learning the value of individual
measurements. The Privacy Preserving Measurement (PPM) work will standardize
techniques for deployment of these techniques on the Internet. This
will include mechanisms for:
         
- Client submission of individual measurements, including proofs of validity.
- Verification of validity proofs by the servers
- Computation of aggregate values by the servers and reporting of
  results to the entity taking the measurement
  
Configuration of clients and servers is out of scope for the working
group. It is assumed that this happens out of band as part of the
PPM service. 

The WG will deliver one or protocols which can accommodate multiple
PPM algorithms. The initial deliverable will support measurements of simple
predefined statistical aggregates such as averages, as well as measurement of "heavy hitters" out of the
set of arbitrary strings submitted by users.  The PPM protocols will use
cryptographic algorithms defined by the CFRG.

The starting point for PDA WG discussions shall be [TODO].










            
