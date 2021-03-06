# Document History

   [[ To be removed from the final specification ]]
   
   -00 [[ Working Group Draft ]]

   * Working group draft

   -04

   * Update OAuth MTLS reference to RFC 8705
   * Use the newish RFC v3 XML and HTML format

   -03 
   
   * rework the text around uniqueness requirements on the jti claim in the DPoP proof JWT
   * make tokens a bit smaller by using `htm`, `htu`, and `jkt` rather than `http_method`, `http_uri`, and `jkt#S256` respectively
   * more explicit recommendation to use mTLS if that is available
   * added David Waite as co-author
   * editorial updates 

   -02
   
   * added normalization rules for URIs
   * removed distinction between proof and binding
   * "jwk" header again used instead of "cnf" claim in DPoP proof
   * renamed "Bearer-DPoP" token type to "DPoP"
   * removed ability for key rotation
   * added security considerations on request integrity
   * explicit advice on extending DPoP proofs to sign other parts of the HTTP messages
   * only use the jkt#S256 in ATs
   * iat instead of exp in DPoP proof JWTs
   * updated guidance on token_type evaluation


   -01
   
   * fixed inconsistencies
   * moved binding and proof messages to headers instead of parameters
   * extracted and unified definition of DPoP JWTs
   * improved description


   -00 

   *  first draft
   

   
