<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.rdbms.server" id="_FZzs0LfJEe-iaoMtKSubDA" name="DATA" md:ref="resource.md#UUID_MD_RDBMS_ORACLE?fileId=UUID_MD_RDBMS_ORACLE$type=md$name=Oracle?" internalVersion="v2.0.0">
  <attribute defType="com.stambia.rdbms.server.module" id="_FgWZsLfJEe-iaoMtKSubDA" value="Oracle"/>
  <attribute defType="com.stambia.rdbms.server.user" id="_hiJ3kLfJEe-iaoMtKSubDA" value="CSG1_ORA4"/>
  <attribute defType="com.stambia.rdbms.server.driver" id="_hiJ3kbfJEe-iaoMtKSubDA" value="oracle.jdbc.OracleDriver"/>
  <attribute defType="com.stambia.rdbms.server.designerAutoCommit" id="_hiLFsLfJEe-iaoMtKSubDA" value="true"/>
  <attribute defType="com.stambia.rdbms.server.password" id="_hiLswLfJEe-iaoMtKSubDA" value="E887CA1CF8D875D88B286A9B0DB0D6F1"/>
  <attribute defType="com.stambia.rdbms.server.url" id="_hiLswbfJEe-iaoMtKSubDA" value="jdbc:oracle:thin:@195.83.93.26 :1521/SIAD_PDB2"/>
  <node defType="com.stambia.rdbms.schema" id="_FrPbELfJEe-iaoMtKSubDA" name="CSG1_ORA4">
    <attribute defType="com.stambia.rdbms.schema.name" id="_FtePsLfJEe-iaoMtKSubDA" value="CSG1_ORA4"/>
    <attribute defType="com.stambia.rdbms.schema.rejectMask" id="_Ftfd0LfJEe-iaoMtKSubDA" value="R_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.loadMask" id="_FtgE4LfJEe-iaoMtKSubDA" value="L[number]_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.integrationMask" id="_FthTALfJEe-iaoMtKSubDA" value="I_[targetName]"/>
    <node defType="com.stambia.rdbms.datastore" id="_hinLB7fJEe-iaoMtKSubDA" name="DWH_ADRESSE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_hinLCLfJEe-iaoMtKSubDA" value="DWH_ADRESSE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_hinLCbfJEe-iaoMtKSubDA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_hinLCrfJEe-iaoMtKSubDA" name="ID_ADRESSE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinLC7fJEe-iaoMtKSubDA" value="ID_ADRESSE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinLDLfJEe-iaoMtKSubDA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinLDbfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinLDrfJEe-iaoMtKSubDA" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinLD7fJEe-iaoMtKSubDA" name="ID_CLIENT" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinLELfJEe-iaoMtKSubDA" value="ID_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinLEbfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinLErfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinLE7fJEe-iaoMtKSubDA" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinLFLfJEe-iaoMtKSubDA" name="LIGNE1" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinLFbfJEe-iaoMtKSubDA" value="LIGNE1"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinLFrfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinLF7fJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinLGLfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinLGbfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinLGrfJEe-iaoMtKSubDA" name="LIGNE2" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinLG7fJEe-iaoMtKSubDA" value="LIGNE2"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinLHLfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinLHbfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinLHrfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinLH7fJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinLILfJEe-iaoMtKSubDA" name="LIGNE3" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinLIbfJEe-iaoMtKSubDA" value="LIGNE3"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinLIrfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinLI7fJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinLJLfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinLJbfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinLJrfJEe-iaoMtKSubDA" name="LIGNE4" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinLJ7fJEe-iaoMtKSubDA" value="LIGNE4"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinLKLfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinLKbfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinLKrfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinLK7fJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinLLLfJEe-iaoMtKSubDA" name="LIGNE5" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinLLbfJEe-iaoMtKSubDA" value="LIGNE5"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinLLrfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinLL7fJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinLMLfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinLMbfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinLMrfJEe-iaoMtKSubDA" name="CODE_POSTAL" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinLM7fJEe-iaoMtKSubDA" value="CODE_POSTAL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinLNLfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinLNbfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinLNrfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinLN7fJEe-iaoMtKSubDA" value="20"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinLOLfJEe-iaoMtKSubDA" name="VILLE" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinLObfJEe-iaoMtKSubDA" value="VILLE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinLOrfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinLO7fJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinLPLfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinLPbfJEe-iaoMtKSubDA" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinLPrfJEe-iaoMtKSubDA" name="PAYS" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinLP7fJEe-iaoMtKSubDA" value="PAYS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinLQLfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinLQbfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinxoLfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinxobfJEe-iaoMtKSubDA" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinxorfJEe-iaoMtKSubDA" name="DATE_DE_CREATION" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinxo7fJEe-iaoMtKSubDA" value="DATE_DE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinxpLfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinxpbfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinxprfJEe-iaoMtKSubDA" value="TIMESTAMP"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinxp7fJEe-iaoMtKSubDA" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinxqLfJEe-iaoMtKSubDA" name="STATUT_ADRESSE" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinxqbfJEe-iaoMtKSubDA" value="STATUT_ADRESSE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinxqrfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinxq7fJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinxrLfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinxrbfJEe-iaoMtKSubDA" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinxrrfJEe-iaoMtKSubDA" name="ID_FICHIER" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinxr7fJEe-iaoMtKSubDA" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinxsLfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinxsbfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinxsrfJEe-iaoMtKSubDA" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_hinxs7fJEe-iaoMtKSubDA" name="SYS_C0037048">
        <node defType="com.stambia.rdbms.colref" id="_hinxtLfJEe-iaoMtKSubDA" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_hinxtbfJEe-iaoMtKSubDA" ref="resource.md#_hinLCrfJEe-iaoMtKSubDA?fileId=_FZzs0LfJEe-iaoMtKSubDA$type=md$name=ID_ADRESSE?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.check" id="_6wEKcbtLEe-m5b-WgwpGlQ" name="CK_ADRESSE_CLIENT">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_8z1ZALtLEe-m5b-WgwpGlQ" value="Adresse pas associé à un client "/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_9uoNULtLEe-m5b-WgwpGlQ" value="ADR001"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_-ucEgLtLEe-m5b-WgwpGlQ" value="DWH_ADRESSE.ID_CLIENT is not null"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_q0emWsSXEe-m4akLKa8hrQ" name="DWH_ADRESSE">
        <node defType="com.stambia.rdbms.colref" id="_q0emW8SXEe-m4akLKa8hrQ" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_q0emXMSXEe-m4akLKa8hrQ" ref="resource.md#_hinLD7fJEe-iaoMtKSubDA?fileId=_FZzs0LfJEe-iaoMtKSubDA$type=md$name=ID_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.check" id="_2n028MYFEe-8earIxX1aJA" name="CONTROLE_STATUT">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_2n028cYFEe-8earIxX1aJA" value="La valeur du statut n'est pas conforme"/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_2n028sYFEe-8earIxX1aJA" value="TEL002"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_2n0288YFEe-8earIxX1aJA" value="DWH_ADRESSE.STATUT_ADRESSE IN ('0','1','2')"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_hinx4LfJEe-iaoMtKSubDA" name="SAS_COMPTE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_hinx4bfJEe-iaoMtKSubDA" value="SAS_COMPTE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_hinx4rfJEe-iaoMtKSubDA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_hinx47fJEe-iaoMtKSubDA" name="CLE_COMPTE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinx5LfJEe-iaoMtKSubDA" value="CLE_COMPTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinx5bfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinx5rfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinx57fJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinx6LfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinx6bfJEe-iaoMtKSubDA" name="ACTION" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinx6rfJEe-iaoMtKSubDA" value="ACTION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinx67fJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinx7LfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinx7bfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinx7rfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinx77fJEe-iaoMtKSubDA" name="STATUS" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinx8LfJEe-iaoMtKSubDA" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinx8bfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinx8rfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinx87fJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinx9LfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinx9bfJEe-iaoMtKSubDA" name="TYPE" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinx9rfJEe-iaoMtKSubDA" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinx97fJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinx-LfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinx-bfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinx-rfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinx-7fJEe-iaoMtKSubDA" name="CABINET" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinx_LfJEe-iaoMtKSubDA" value="CABINET"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinx_bfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinx_rfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinx_7fJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinyALfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinyAbfJEe-iaoMtKSubDA" name="DATE_CREATION" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinyArfJEe-iaoMtKSubDA" value="DATE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinyA7fJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinyBLfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinyBbfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinyBrfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinyB7fJEe-iaoMtKSubDA" name="ID_FICHIER" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinyCLfJEe-iaoMtKSubDA" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinyCbfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinyCrfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinyC7fJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinyDLfJEe-iaoMtKSubDA" value="255"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_hipnqbfJEe-iaoMtKSubDA" name="SAS_TELEPHONE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_hipnqrfJEe-iaoMtKSubDA" value="SAS_TELEPHONE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_hipnq7fJEe-iaoMtKSubDA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_hipnrLfJEe-iaoMtKSubDA" name="CLE_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_hipnrbfJEe-iaoMtKSubDA" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hipnrrfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hipnr7fJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hipnsLfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hipnsbfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hipnsrfJEe-iaoMtKSubDA" name="ACTION" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_hipns7fJEe-iaoMtKSubDA" value="ACTION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hipntLfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hipntbfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hipntrfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hipnt7fJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hipnuLfJEe-iaoMtKSubDA" name="PHONE" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_hipnubfJEe-iaoMtKSubDA" value="PHONE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hipnurfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hipnu7fJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hipnvLfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hipnvbfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hipnvrfJEe-iaoMtKSubDA" name="STATUS" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_hipnv7fJEe-iaoMtKSubDA" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hipnwLfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hipnwbfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hipnwrfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hipnw7fJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hipnxLfJEe-iaoMtKSubDA" name="FAVORI" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_hipnxbfJEe-iaoMtKSubDA" value="FAVORI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hipnxrfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hipnx7fJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hipnyLfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hipnybfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hipnyrfJEe-iaoMtKSubDA" name="TYPE" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_hipny7fJEe-iaoMtKSubDA" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hipnzLfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hipnzbfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hipnzrfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hipnz7fJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hiqN4LfJEe-iaoMtKSubDA" name="DATE_CREATION" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_hiqN4bfJEe-iaoMtKSubDA" value="DATE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hiqN4rfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hiqN47fJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hiqN5LfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hiqN5bfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hiqN5rfJEe-iaoMtKSubDA" name="ID_FICHIER" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_hiqN57fJEe-iaoMtKSubDA" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hiqN6LfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hiqN6bfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hiqN6rfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hiqN67fJEe-iaoMtKSubDA" value="255"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_hinKvLfJEe-iaoMtKSubDA" name="SAS_CLIENT">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_hinKvbfJEe-iaoMtKSubDA" value="SAS_CLIENT"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_hinKvrfJEe-iaoMtKSubDA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_hinKv7fJEe-iaoMtKSubDA" name="CLE_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinKwLfJEe-iaoMtKSubDA" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinKwbfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinKwrfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinKw7fJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinKxLfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinKxbfJEe-iaoMtKSubDA" name="CLE_COMPTE" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinKxrfJEe-iaoMtKSubDA" value="CLE_COMPTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinKx7fJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinKyLfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinKybfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinKyrfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinKy7fJEe-iaoMtKSubDA" name="STATUS" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinKzLfJEe-iaoMtKSubDA" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinKzbfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinKzrfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinKz7fJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinK0LfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinK0bfJEe-iaoMtKSubDA" name="TYPE" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinK0rfJEe-iaoMtKSubDA" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinK07fJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinK1LfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinK1bfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinK1rfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinK17fJEe-iaoMtKSubDA" name="CIVILITE" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinK2LfJEe-iaoMtKSubDA" value="CIVILITE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinK2bfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinK2rfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinK27fJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinK3LfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinK3bfJEe-iaoMtKSubDA" name="PRENOM" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinK3rfJEe-iaoMtKSubDA" value="PRENOM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinK37fJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinK4LfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinK4bfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinK4rfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinK47fJEe-iaoMtKSubDA" name="NOM" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinK5LfJEe-iaoMtKSubDA" value="NOM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinK5bfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinK5rfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinK57fJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinK6LfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinK6bfJEe-iaoMtKSubDA" name="DATE_ANNIVERSAIRE" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinK6rfJEe-iaoMtKSubDA" value="DATE_ANNIVERSAIRE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinK67fJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinK7LfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinK7bfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinK7rfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinK77fJEe-iaoMtKSubDA" name="SEXE" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinK8LfJEe-iaoMtKSubDA" value="SEXE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinK8bfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinK8rfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinK87fJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinK9LfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinK9bfJEe-iaoMtKSubDA" name="MUTUELLE" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinK9rfJEe-iaoMtKSubDA" value="MUTUELLE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinK97fJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinK-LfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinK-bfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinK-rfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinK-7fJEe-iaoMtKSubDA" name="DATE_CREATION" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinK_LfJEe-iaoMtKSubDA" value="DATE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinK_bfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinK_rfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinK_7fJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinLALfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinLAbfJEe-iaoMtKSubDA" name="ID_FICHIER" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinLArfJEe-iaoMtKSubDA" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinLA7fJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinLBLfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinLBbfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinLBrfJEe-iaoMtKSubDA" value="255"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_hisDXrfJEe-iaoMtKSubDA" name="SAS_ADRESSE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_hisDX7fJEe-iaoMtKSubDA" value="SAS_ADRESSE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_hisDYLfJEe-iaoMtKSubDA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_hisDYbfJEe-iaoMtKSubDA" name="CLE_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_hisDYrfJEe-iaoMtKSubDA" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hisDY7fJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hisDZLfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hisDZbfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hisDZrfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hisDZ7fJEe-iaoMtKSubDA" name="ACTION" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_hisDaLfJEe-iaoMtKSubDA" value="ACTION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hisDabfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hisDarfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hisDa7fJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hisDbLfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hisDbbfJEe-iaoMtKSubDA" name="STATUS" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_hisDbrfJEe-iaoMtKSubDA" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hisDb7fJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hisDcLfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hisDcbfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hisDcrfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hisDc7fJEe-iaoMtKSubDA" name="LIGNE_1" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_hisDdLfJEe-iaoMtKSubDA" value="LIGNE_1"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hisDdbfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hisDdrfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hisDd7fJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hisDeLfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hisDebfJEe-iaoMtKSubDA" name="LIGNE_2" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_hisDerfJEe-iaoMtKSubDA" value="LIGNE_2"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hisDe7fJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hisDfLfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hisDfbfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hisDfrfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hisDf7fJEe-iaoMtKSubDA" name="LIGNE_3" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_hisDgLfJEe-iaoMtKSubDA" value="LIGNE_3"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hisDgbfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hisDgrfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hisDg7fJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hisDhLfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hisDhbfJEe-iaoMtKSubDA" name="LIGNE_4" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_hisDhrfJEe-iaoMtKSubDA" value="LIGNE_4"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hisDh7fJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hisDiLfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hisDibfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hisDirfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hisDi7fJEe-iaoMtKSubDA" name="LIGNE_5" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_hisDjLfJEe-iaoMtKSubDA" value="LIGNE_5"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hisDjbfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hisDjrfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hisDj7fJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hisDkLfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hisDkbfJEe-iaoMtKSubDA" name="VILLE" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_hisDkrfJEe-iaoMtKSubDA" value="VILLE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hisDk7fJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hisDlLfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hisDlbfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hisDlrfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hisDl7fJEe-iaoMtKSubDA" name="CODE_POSTAL" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_hisDmLfJEe-iaoMtKSubDA" value="CODE_POSTAL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hisDmbfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hisDmrfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hisDm7fJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hisDnLfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hisDnbfJEe-iaoMtKSubDA" name="PAYS" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_hisDnrfJEe-iaoMtKSubDA" value="PAYS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hisDn7fJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hisDoLfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hisDobfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hisDorfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hisDo7fJEe-iaoMtKSubDA" name="QUALITE" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_hisDpLfJEe-iaoMtKSubDA" value="QUALITE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hisDpbfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hisDprfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hisDp7fJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hisDqLfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hisDqbfJEe-iaoMtKSubDA" name="DATE_CREATION" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_hisDqrfJEe-iaoMtKSubDA" value="DATE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hisDq7fJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hisDrLfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hisDrbfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hisDrrfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hisDr7fJEe-iaoMtKSubDA" name="ID_FICHIER" position="14">
        <attribute defType="com.stambia.rdbms.column.name" id="_hisDsLfJEe-iaoMtKSubDA" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hisDsbfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hisDsrfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hisDs7fJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hisDtLfJEe-iaoMtKSubDA" value="255"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_hioY_bfJEe-iaoMtKSubDA" name="SAS_EMAIL">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_hioY_rfJEe-iaoMtKSubDA" value="SAS_EMAIL"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_hioY_7fJEe-iaoMtKSubDA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_hioZALfJEe-iaoMtKSubDA" name="CLE_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_hioZAbfJEe-iaoMtKSubDA" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hioZArfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hioZA7fJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hioZBLfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hioZBbfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hioZBrfJEe-iaoMtKSubDA" name="ACTION" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_hioZB7fJEe-iaoMtKSubDA" value="ACTION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hioZCLfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hioZCbfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hioZCrfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hioZC7fJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hioZDLfJEe-iaoMtKSubDA" name="EMAIL" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_hioZDbfJEe-iaoMtKSubDA" value="EMAIL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hioZDrfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hioZD7fJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hioZELfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hioZEbfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hioZErfJEe-iaoMtKSubDA" name="STATUS" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_hioZE7fJEe-iaoMtKSubDA" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hioZFLfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hioZFbfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hioZFrfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hioZF7fJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hioZGLfJEe-iaoMtKSubDA" name="DATE_CREATION" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_hioZGbfJEe-iaoMtKSubDA" value="DATE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hioZGrfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hioZG7fJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hioZHLfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hioZHbfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hioZHrfJEe-iaoMtKSubDA" name="ID_FICHIER" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_hioZH7fJEe-iaoMtKSubDA" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hioZILfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hioZIbfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hioZIrfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hioZI7fJEe-iaoMtKSubDA" value="255"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_hio_4bfJEe-iaoMtKSubDA" name="TABLE_FILE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_hio_4rfJEe-iaoMtKSubDA" value="TABLE_FILE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_hio_47fJEe-iaoMtKSubDA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_hio_5LfJEe-iaoMtKSubDA" name="FILE_NAME" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_hio_5bfJEe-iaoMtKSubDA" value="FILE_NAME"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hio_5rfJEe-iaoMtKSubDA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hio_57fJEe-iaoMtKSubDA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hio_6LfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hio_6bfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hio_6rfJEe-iaoMtKSubDA" name="CHAMP1" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_hio_67fJEe-iaoMtKSubDA" value="CHAMP1"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hio_7LfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hio_7bfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hio_7rfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hio_77fJEe-iaoMtKSubDA" value="100"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hio_8LfJEe-iaoMtKSubDA" name="CHAMP2" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_hio_8bfJEe-iaoMtKSubDA" value="CHAMP2"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hio_8rfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hio_87fJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hio_9LfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hio_9bfJEe-iaoMtKSubDA" value="100"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hio_9rfJEe-iaoMtKSubDA" name="CHAMP3" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_hio_97fJEe-iaoMtKSubDA" value="CHAMP3"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hio_-LfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hio_-bfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hio_-rfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hio_-7fJEe-iaoMtKSubDA" value="100"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hio__LfJEe-iaoMtKSubDA" name="CHAMP4" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_hio__bfJEe-iaoMtKSubDA" value="CHAMP4"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hio__rfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hio__7fJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hipAALfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hipAAbfJEe-iaoMtKSubDA" value="100"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hipAArfJEe-iaoMtKSubDA" name="CHAMP5" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_hipAA7fJEe-iaoMtKSubDA" value="CHAMP5"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hipABLfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hipABbfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hipABrfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hipAB7fJEe-iaoMtKSubDA" value="100"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hipACLfJEe-iaoMtKSubDA" name="CHAMP6" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_hipACbfJEe-iaoMtKSubDA" value="CHAMP6"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hipACrfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hipAC7fJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hipADLfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hipADbfJEe-iaoMtKSubDA" value="100"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hipADrfJEe-iaoMtKSubDA" name="CHAMP7" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_hipAD7fJEe-iaoMtKSubDA" value="CHAMP7"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hipAELfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hipAEbfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hipAErfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hipAE7fJEe-iaoMtKSubDA" value="100"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hipAFLfJEe-iaoMtKSubDA" name="CHAMP8" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_hipAFbfJEe-iaoMtKSubDA" value="CHAMP8"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hipAFrfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hipAF7fJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hipAGLfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hipAGbfJEe-iaoMtKSubDA" value="100"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hipAGrfJEe-iaoMtKSubDA" name="CHAMP9" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_hipAG7fJEe-iaoMtKSubDA" value="CHAMP9"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hipAHLfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hipAHbfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hipAHrfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hipAH7fJEe-iaoMtKSubDA" value="100"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hipAILfJEe-iaoMtKSubDA" name="CHAMP10" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_hipAIbfJEe-iaoMtKSubDA" value="CHAMP10"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hipAIrfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hipAI7fJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hipAJLfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hipAJbfJEe-iaoMtKSubDA" value="100"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hipAJrfJEe-iaoMtKSubDA" name="CHAMP11" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_hipAJ7fJEe-iaoMtKSubDA" value="CHAMP11"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hipAKLfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hipAKbfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hipAKrfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hipAK7fJEe-iaoMtKSubDA" value="100"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hipALLfJEe-iaoMtKSubDA" name="CHAMP12" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_hipALbfJEe-iaoMtKSubDA" value="CHAMP12"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hipALrfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hipAL7fJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hipAMLfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hipAMbfJEe-iaoMtKSubDA" value="100"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hipAMrfJEe-iaoMtKSubDA" name="CHAMP13" position="14">
        <attribute defType="com.stambia.rdbms.column.name" id="_hipAM7fJEe-iaoMtKSubDA" value="CHAMP13"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hipANLfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hipANbfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hipANrfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hipAN7fJEe-iaoMtKSubDA" value="100"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_hiq1LbfJEe-iaoMtKSubDA" name="FILE_SOURCE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_hiq1LrfJEe-iaoMtKSubDA" value="FILE_SOURCE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_hiq1L7fJEe-iaoMtKSubDA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_hiq1MLfJEe-iaoMtKSubDA" name="ID_SOURCE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_hiq1MbfJEe-iaoMtKSubDA" value="ID_SOURCE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hiq1MrfJEe-iaoMtKSubDA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hiq1M7fJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hiq1NLfJEe-iaoMtKSubDA" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hiq1NbfJEe-iaoMtKSubDA" name="SOURCE" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_hiq1NrfJEe-iaoMtKSubDA" value="SOURCE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hiq1N7fJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hiq1OLfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hiq1ObfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hiq1OrfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hiq1O7fJEe-iaoMtKSubDA" name="DATE_INTEGRATION" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_hiq1PLfJEe-iaoMtKSubDA" value="DATE_INTEGRATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hiq1PbfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_hiq1PrfJEe-iaoMtKSubDA" value="6"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hiq1P7fJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hiq1QLfJEe-iaoMtKSubDA" value="TIMESTAMP(6)"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hiq1QbfJEe-iaoMtKSubDA" value="11"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_hiq1QrfJEe-iaoMtKSubDA" name="SYS_C0036550">
        <node defType="com.stambia.rdbms.colref" id="_hiq1Q7fJEe-iaoMtKSubDA" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_hiq1RLfJEe-iaoMtKSubDA" ref="resource.md#_hiq1MLfJEe-iaoMtKSubDA?fileId=_FZzs0LfJEe-iaoMtKSubDA$type=md$name=ID_SOURCE?"/>
        </node>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_hinxtrfJEe-iaoMtKSubDA" name="TRANSCO">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_hinxt7fJEe-iaoMtKSubDA" value="TRANSCO"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_hinxuLfJEe-iaoMtKSubDA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_hinxubfJEe-iaoMtKSubDA" name="CONTEXTE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinxurfJEe-iaoMtKSubDA" value="CONTEXTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinxu7fJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinxvLfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinxvbfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinxvrfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinxv7fJEe-iaoMtKSubDA" name="SOURCE_CODE" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinxwLfJEe-iaoMtKSubDA" value="SOURCE_CODE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinxwbfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinxwrfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinxw7fJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinxxLfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinxxbfJEe-iaoMtKSubDA" name="TARGET_VALUE" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinxxrfJEe-iaoMtKSubDA" value="TARGET_VALUE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinxx7fJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinxyLfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinxybfJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinxyrfJEe-iaoMtKSubDA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hinxy7fJEe-iaoMtKSubDA" name="DESCRIPTION" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_hinxzLfJEe-iaoMtKSubDA" value="DESCRIPTION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hinxzbfJEe-iaoMtKSubDA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hinxzrfJEe-iaoMtKSubDA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hinxz7fJEe-iaoMtKSubDA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hinx0LfJEe-iaoMtKSubDA" value="255"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_Y1lzEsR8Ee-LvsLQvAjjow" name="DWH_COMPTE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_Y1lzE8R8Ee-LvsLQvAjjow" value="DWH_COMPTE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_Y1lzFMR8Ee-LvsLQvAjjow" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_Y1lzFcR8Ee-LvsLQvAjjow" name="ID_COMPTE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_Y1lzFsR8Ee-LvsLQvAjjow" value="ID_COMPTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Y1lzF8R8Ee-LvsLQvAjjow" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Y1lzGMR8Ee-LvsLQvAjjow" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Y1lzGcR8Ee-LvsLQvAjjow" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Y1lzGsR8Ee-LvsLQvAjjow" name="CLE_COMPTE" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_Y1lzG8R8Ee-LvsLQvAjjow" value="CLE_COMPTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Y1mZ4MR8Ee-LvsLQvAjjow" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Y1mZ4cR8Ee-LvsLQvAjjow" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Y1mZ4sR8Ee-LvsLQvAjjow" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Y1mZ48R8Ee-LvsLQvAjjow" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Y1mZ5MR8Ee-LvsLQvAjjow" name="STATUS" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_Y1mZ5cR8Ee-LvsLQvAjjow" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Y1mZ5sR8Ee-LvsLQvAjjow" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Y1mZ58R8Ee-LvsLQvAjjow" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Y1mZ6MR8Ee-LvsLQvAjjow" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Y1mZ6cR8Ee-LvsLQvAjjow" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Y1mZ6sR8Ee-LvsLQvAjjow" name="TYPE" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_Y1mZ68R8Ee-LvsLQvAjjow" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Y1mZ7MR8Ee-LvsLQvAjjow" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Y1mZ7cR8Ee-LvsLQvAjjow" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Y1mZ7sR8Ee-LvsLQvAjjow" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Y1mZ78R8Ee-LvsLQvAjjow" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Y1mZ8MR8Ee-LvsLQvAjjow" name="CABINET" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_Y1mZ8cR8Ee-LvsLQvAjjow" value="CABINET"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Y1mZ8sR8Ee-LvsLQvAjjow" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Y1mZ88R8Ee-LvsLQvAjjow" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Y1mZ9MR8Ee-LvsLQvAjjow" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Y1mZ9cR8Ee-LvsLQvAjjow" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Y1mZ9sR8Ee-LvsLQvAjjow" name="DATE_CREATION" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_Y1mZ98R8Ee-LvsLQvAjjow" value="DATE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Y1mZ-MR8Ee-LvsLQvAjjow" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_Y1mZ-cR8Ee-LvsLQvAjjow" value="6"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Y1mZ-sR8Ee-LvsLQvAjjow" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Y1mZ-8R8Ee-LvsLQvAjjow" value="TIMESTAMP"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Y1mZ_MR8Ee-LvsLQvAjjow" value="11"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Y1mZ_cR8Ee-LvsLQvAjjow" name="ID_FICHIER" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_Y1mZ_sR8Ee-LvsLQvAjjow" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Y1mZ_8R8Ee-LvsLQvAjjow" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Y1maAMR8Ee-LvsLQvAjjow" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Y1maAcR8Ee-LvsLQvAjjow" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Y1maAsR8Ee-LvsLQvAjjow" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_Y1maA8R8Ee-LvsLQvAjjow" name="DWH_COMPTE">
        <node defType="com.stambia.rdbms.colref" id="_Y1maBMR8Ee-LvsLQvAjjow" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_Y1maBcR8Ee-LvsLQvAjjow" ref="resource.md#_Y1lzGsR8Ee-LvsLQvAjjow?fileId=_FZzs0LfJEe-iaoMtKSubDA$type=md$name=CLE_COMPTE?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.check" id="_qUpqscR8Ee-LvsLQvAjjow" name="CK_CLE_COMPTE">
        <attribute defType="com.stambia.rdbms.check.sql" id="_sFyRIMR8Ee-LvsLQvAjjow" value="DWH_COMPTE.CLE_COMPTE is not null"/>
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_ZxQH0MSSEe-m4akLKa8hrQ" value="clé compte non renseigné "/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_a433MMSSEe-m4akLKa8hrQ" value="CPTE002"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_iDJZkcVjEe-8earIxX1aJA" name="CK_CABINET">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_mHMd0MVjEe-8earIxX1aJA" value="Cabinet non renseigné ou pas dans la liste"/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_pl71kMVjEe-8earIxX1aJA" value="CPTE001"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_qwe9IMVjEe-8earIxX1aJA" value="DWH_COMPTE.CABINET in ('Valenciennes','Marcq en Baroeul','Wattrelos','Douai','Villeneuve d ascq','Dunkerque','Tourcoing','Roubaix','Lille')"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_esIBIcVoEe-8earIxX1aJA" name="Controle_TYPE">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_hZF9sMVoEe-8earIxX1aJA" value="Le type de compte n'est pas valable"/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_kR594MVoEe-8earIxX1aJA" value="CPT003"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_mm9wwMVoEe-8earIxX1aJA" value="DWH_COMPTE.TYPE is not null"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_Aezr1MSVEe-m4akLKa8hrQ" name="DWH_CLIENT">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_Aezr1cSVEe-m4akLKa8hrQ" value="DWH_CLIENT"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_Aezr1sSVEe-m4akLKa8hrQ" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_Aezr18SVEe-m4akLKa8hrQ" name="ID_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_Aezr2MSVEe-m4akLKa8hrQ" value="ID_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Aezr2cSVEe-m4akLKa8hrQ" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Aezr2sSVEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Aezr28SVEe-m4akLKa8hrQ" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Aezr3MSVEe-m4akLKa8hrQ" name="CLE_CLIENT" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_Aezr3cSVEe-m4akLKa8hrQ" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Aezr3sSVEe-m4akLKa8hrQ" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Aezr38SVEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Aezr4MSVEe-m4akLKa8hrQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Aezr4cSVEe-m4akLKa8hrQ" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Aezr4sSVEe-m4akLKa8hrQ" name="STATUT_DU_CLIENT" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_Aezr48SVEe-m4akLKa8hrQ" value="STATUT_DU_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Aezr5MSVEe-m4akLKa8hrQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Aezr5cSVEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Aezr5sSVEe-m4akLKa8hrQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Aezr58SVEe-m4akLKa8hrQ" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Aezr6MSVEe-m4akLKa8hrQ" name="TYPE_DE_CLIENT" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_Aezr6cSVEe-m4akLKa8hrQ" value="TYPE_DE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Aezr6sSVEe-m4akLKa8hrQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Aezr68SVEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Aezr7MSVEe-m4akLKa8hrQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Aezr7cSVEe-m4akLKa8hrQ" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Aezr7sSVEe-m4akLKa8hrQ" name="CIVILITE" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_Aezr78SVEe-m4akLKa8hrQ" value="CIVILITE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Aezr8MSVEe-m4akLKa8hrQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Aezr8cSVEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Aezr8sSVEe-m4akLKa8hrQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Aezr88SVEe-m4akLKa8hrQ" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Aezr9MSVEe-m4akLKa8hrQ" name="PRENOM" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_Aezr9cSVEe-m4akLKa8hrQ" value="PRENOM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Aezr9sSVEe-m4akLKa8hrQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Aezr98SVEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Aezr-MSVEe-m4akLKa8hrQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Aezr-cSVEe-m4akLKa8hrQ" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Aezr-sSVEe-m4akLKa8hrQ" name="NOM" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_Aezr-8SVEe-m4akLKa8hrQ" value="NOM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Aezr_MSVEe-m4akLKa8hrQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Aezr_cSVEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Aezr_sSVEe-m4akLKa8hrQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Aezr_8SVEe-m4akLKa8hrQ" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_AezsAMSVEe-m4akLKa8hrQ" name="DATE_ANNIVERSAIRE" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_AezsAcSVEe-m4akLKa8hrQ" value="DATE_ANNIVERSAIRE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_AezsAsSVEe-m4akLKa8hrQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_AezsA8SVEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_AezsBMSVEe-m4akLKa8hrQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_AezsBcSVEe-m4akLKa8hrQ" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_AezsBsSVEe-m4akLKa8hrQ" name="SEXE" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_AezsB8SVEe-m4akLKa8hrQ" value="SEXE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_AezsCMSVEe-m4akLKa8hrQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_AezsCcSVEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_AezsCsSVEe-m4akLKa8hrQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_AezsC8SVEe-m4akLKa8hrQ" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_AezsDMSVEe-m4akLKa8hrQ" name="MUTUELLE" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_AezsDcSVEe-m4akLKa8hrQ" value="MUTUELLE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_AezsDsSVEe-m4akLKa8hrQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_AezsD8SVEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_AezsEMSVEe-m4akLKa8hrQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_AezsEcSVEe-m4akLKa8hrQ" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_AezsEsSVEe-m4akLKa8hrQ" name="DATE_DE_CREATION" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_AezsE8SVEe-m4akLKa8hrQ" value="DATE_DE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_AezsFMSVEe-m4akLKa8hrQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_AezsFcSVEe-m4akLKa8hrQ" value="6"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_AezsFsSVEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_AezsF8SVEe-m4akLKa8hrQ" value="TIMESTAMP"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_AezsGMSVEe-m4akLKa8hrQ" value="11"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_AezsGcSVEe-m4akLKa8hrQ" name="ID_COMPTE" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_AezsGsSVEe-m4akLKa8hrQ" value="ID_COMPTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_AezsG8SVEe-m4akLKa8hrQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_AezsHMSVEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_AezsHcSVEe-m4akLKa8hrQ" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_AezsHsSVEe-m4akLKa8hrQ" name="ID_FICHIER" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_AezsH8SVEe-m4akLKa8hrQ" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_AezsIMSVEe-m4akLKa8hrQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_AezsIcSVEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_AezsIsSVEe-m4akLKa8hrQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_AezsI8SVEe-m4akLKa8hrQ" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_AezsJMSVEe-m4akLKa8hrQ" name="DWH_CLIENT">
        <node defType="com.stambia.rdbms.colref" id="_AezsJcSVEe-m4akLKa8hrQ" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_AezsJsSVEe-m4akLKa8hrQ" ref="resource.md#_Aezr3MSVEe-m4akLKa8hrQ?fileId=_FZzs0LfJEe-iaoMtKSubDA$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.check" id="_gwuUAcSVEe-m4akLKa8hrQ" name="FK_COMPTE_CLIENT">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_n1msAMSVEe-m4akLKa8hrQ" value="pas de compte associe"/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_pA5acMSVEe-m4akLKa8hrQ" value="CLIENT_001"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_qzvREMSVEe-m4akLKa8hrQ" value="DWH_CLIENT.ID_COMPTE is not null"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_0SRoEcSVEe-m4akLKa8hrQ" name="CK_CLE_CLIENT">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_4GUhcMSVEe-m4akLKa8hrQ" value="clé client non renseigné "/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_5IyrEMSVEe-m4akLKa8hrQ" value="CLT002"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_64H6sMSVEe-m4akLKa8hrQ" value="DWH_CLIENT.CLE_CLIENT is not null"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_XjZEoMX8Ee-8earIxX1aJA" name="Controle CIVILITE">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_rdA6cMX8Ee-8earIxX1aJA" value="La valeur de la civilité n'est pas conforme"/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_vJkrwMX8Ee-8earIxX1aJA" value="CLIENT_003"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_xMKOkMX8Ee-8earIxX1aJA" value="DWH_CLIENT.CIVILITE is not null"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_HUByscX_Ee-8earIxX1aJA" name="Controle SEXE">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_JHVjYMX_Ee-8earIxX1aJA" value="La valeur du sexe n'est pas conforme"/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_LU61QMX_Ee-8earIxX1aJA" value="CLIENT_004"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_M37gIMX_Ee-8earIxX1aJA" value="DWH_CLIENT.SEXE is not null "/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_inTWocX_Ee-8earIxX1aJA" name="controle MUTUELLE">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_mLjggMX_Ee-8earIxX1aJA" value="la valeur de la mutuelle n'est pas conforme"/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_qz7Z0MX_Ee-8earIxX1aJA" value="CLIENT_005"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_s0gKcMX_Ee-8earIxX1aJA" value="DWH_CLIENT.MUTUELLE is not null AND DWH_CLIENT.MUTUELLE IN ('1','2','3','4','5','6','7','8','9','10','11','12','13')"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_FqzTDcSZEe-m4akLKa8hrQ" name="DWH_EMAIL">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_FqzTDsSZEe-m4akLKa8hrQ" value="DWH_EMAIL"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_FqzTD8SZEe-m4akLKa8hrQ" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_FqzTEMSZEe-m4akLKa8hrQ" name="ID_EMAIL" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_FqzTEcSZEe-m4akLKa8hrQ" value="ID_EMAIL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FqzTEsSZEe-m4akLKa8hrQ" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_FqzTE8SZEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FqzTFMSZEe-m4akLKa8hrQ" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_FqzTFcSZEe-m4akLKa8hrQ" name="ID_CLIENT" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_FqzTFsSZEe-m4akLKa8hrQ" value="ID_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FqzTF8SZEe-m4akLKa8hrQ" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_FqzTGMSZEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FqzTGcSZEe-m4akLKa8hrQ" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_FqzTGsSZEe-m4akLKa8hrQ" name="EMAIL" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_FqzTG8SZEe-m4akLKa8hrQ" value="EMAIL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FqzTHMSZEe-m4akLKa8hrQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_FqzTHcSZEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FqzTHsSZEe-m4akLKa8hrQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_FqzTH8SZEe-m4akLKa8hrQ" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_FqzTIMSZEe-m4akLKa8hrQ" name="STATUT_EMAIL" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_FqzTIcSZEe-m4akLKa8hrQ" value="STATUT_EMAIL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FqzTIsSZEe-m4akLKa8hrQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_FqzTI8SZEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FqzTJMSZEe-m4akLKa8hrQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_FqzTJcSZEe-m4akLKa8hrQ" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_FqzTJsSZEe-m4akLKa8hrQ" name="DATE_DE_CREATION" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_FqzTJ8SZEe-m4akLKa8hrQ" value="DATE_DE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FqzTKMSZEe-m4akLKa8hrQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_FqzTKcSZEe-m4akLKa8hrQ" value="6"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_FqzTKsSZEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FqzTK8SZEe-m4akLKa8hrQ" value="TIMESTAMP"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_FqzTLMSZEe-m4akLKa8hrQ" value="11"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_FqzTLcSZEe-m4akLKa8hrQ" name="ID_FICHIER" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_FqzTLsSZEe-m4akLKa8hrQ" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_FqzTL8SZEe-m4akLKa8hrQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_FqzTMMSZEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_FqzTMcSZEe-m4akLKa8hrQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_FqzTMsSZEe-m4akLKa8hrQ" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_FqzTM8SZEe-m4akLKa8hrQ" name="DWH_EMAIL">
        <node defType="com.stambia.rdbms.colref" id="_FqzTNMSZEe-m4akLKa8hrQ" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_FqzTNcSZEe-m4akLKa8hrQ" ref="resource.md#_FqzTFcSZEe-m4akLKa8hrQ?fileId=_FZzs0LfJEe-iaoMtKSubDA$type=md$name=ID_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.check" id="_oz5J0cYBEe-8earIxX1aJA" name="Controle EMAIL">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_u6QEEMYBEe-8earIxX1aJA" value="l'email n'est pas conforme "/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_wmKzUMYBEe-8earIxX1aJA" value="EMAIL_001"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_z3hPUMYBEe-8earIxX1aJA" value="DWH_EMAIL.EMAIL LIKE ('%@%.%')"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_zmgVv8SaEe-m4akLKa8hrQ" name="DWH_TELEPHONE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_zmgVwMSaEe-m4akLKa8hrQ" value="DWH_TELEPHONE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_zmgVwcSaEe-m4akLKa8hrQ" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_zmgVwsSaEe-m4akLKa8hrQ" name="ID_TELEPHONE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_zmgVw8SaEe-m4akLKa8hrQ" value="ID_TELEPHONE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_zmgVxMSaEe-m4akLKa8hrQ" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_zmgVxcSaEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_zmgVxsSaEe-m4akLKa8hrQ" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_zmgVx8SaEe-m4akLKa8hrQ" name="ID_CLIENT" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_zmgVyMSaEe-m4akLKa8hrQ" value="ID_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_zmgVycSaEe-m4akLKa8hrQ" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_zmgVysSaEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_zmgVy8SaEe-m4akLKa8hrQ" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_zmgVzMSaEe-m4akLKa8hrQ" name="TYPE" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_zmgVzcSaEe-m4akLKa8hrQ" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_zmgVzsSaEe-m4akLKa8hrQ" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_zmgVz8SaEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_zmgV0MSaEe-m4akLKa8hrQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_zmgV0cSaEe-m4akLKa8hrQ" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_zmgV0sSaEe-m4akLKa8hrQ" name="PHONE" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_zmgV08SaEe-m4akLKa8hrQ" value="PHONE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_zmgV1MSaEe-m4akLKa8hrQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_zmgV1cSaEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_zmgV1sSaEe-m4akLKa8hrQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_zmgV18SaEe-m4akLKa8hrQ" value="20"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_zmgV2MSaEe-m4akLKa8hrQ" name="STATUT_TELEPHONE" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_zmgV2cSaEe-m4akLKa8hrQ" value="STATUT_TELEPHONE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_zmgV2sSaEe-m4akLKa8hrQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_zmgV28SaEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_zmgV3MSaEe-m4akLKa8hrQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_zmgV3cSaEe-m4akLKa8hrQ" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_zmgV3sSaEe-m4akLKa8hrQ" name="FAVORI" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_zmgV38SaEe-m4akLKa8hrQ" value="FAVORI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_zmgV4MSaEe-m4akLKa8hrQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_zmgV4cSaEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_zmgV4sSaEe-m4akLKa8hrQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_zmgV48SaEe-m4akLKa8hrQ" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_zmgV5MSaEe-m4akLKa8hrQ" name="DATE_DE_CREATION" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_zmgV5cSaEe-m4akLKa8hrQ" value="DATE_DE_CREATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_zmgV5sSaEe-m4akLKa8hrQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_zmgV58SaEe-m4akLKa8hrQ" value="6"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_zmgV6MSaEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_zmgV6cSaEe-m4akLKa8hrQ" value="TIMESTAMP"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_zmgV6sSaEe-m4akLKa8hrQ" value="11"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_zmgV68SaEe-m4akLKa8hrQ" name="ID_FICHIER" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_zmgV7MSaEe-m4akLKa8hrQ" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_zmgV7cSaEe-m4akLKa8hrQ" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_zmgV7sSaEe-m4akLKa8hrQ" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_zmgV78SaEe-m4akLKa8hrQ" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_zmgV8MSaEe-m4akLKa8hrQ" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_zmgV8cSaEe-m4akLKa8hrQ" name="DWH_TELEPHONE">
        <node defType="com.stambia.rdbms.colref" id="_zmgV8sSaEe-m4akLKa8hrQ" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_zmgV88SaEe-m4akLKa8hrQ" ref="resource.md#_zmgVx8SaEe-m4akLKa8hrQ?fileId=_FZzs0LfJEe-iaoMtKSubDA$type=md$name=ID_CLIENT?"/>
        </node>
        <node defType="com.stambia.rdbms.colref" id="_zmgV9MSaEe-m4akLKa8hrQ" position="2">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_zmgV9cSaEe-m4akLKa8hrQ" ref="resource.md#_zmgVzMSaEe-m4akLKa8hrQ?fileId=_FZzs0LfJEe-iaoMtKSubDA$type=md$name=TYPE?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.check" id="_FMO4scSfEe-E07p82FnYpQ" name="CK_PHONE_CLIENT">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_MQio8MSfEe-E07p82FnYpQ" value="Telephone pas associé à un client"/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_OLeEkMSfEe-E07p82FnYpQ" value="PHN001"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_PyBLoMSfEe-E07p82FnYpQ" value="DWH_TELEPHONE.ID_CLIENT is not null"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_vNs5ocYDEe-8earIxX1aJA" name="CONTROLE TYPE ">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_yaIZYMYDEe-8earIxX1aJA" value="La valeur du type de télephone n'est pas conforme"/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_2eXD0MYDEe-8earIxX1aJA" value="TEL001"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_3g9JQMYDEe-8earIxX1aJA" value="DWH_TELEPHONE.TYPE IN ('Fixe','Portable')"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_0Yxa4cYEEe-8earIxX1aJA" name="CONTROLE STATUS">
        <attribute defType="com.stambia.rdbms.check.userMessage" id="_2O_VoMYEEe-8earIxX1aJA" value="La valeur du type de télephone n'est pas conforme"/>
        <attribute defType="com.stambia.rdbms.check.rejectCode" id="_3_ZjUMYEEe-8earIxX1aJA" value="TEL002"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_5tjuQMYEEe-8earIxX1aJA" value="DWH_TELEPHONE.STATUT_TELEPHONE IN ('0','1','2')"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_VXT_LsVJEe-gzK1_i2VR3A" name="IND_SESSION_FILE_OP_LST">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_VXT_L8VJEe-gzK1_i2VR3A" value="IND_SESSION_FILE_OP_LST"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_VXT_MMVJEe-gzK1_i2VR3A" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_VXT_McVJEe-gzK1_i2VR3A" name="SESS_ID" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXT_MsVJEe-gzK1_i2VR3A" value="SESS_ID"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXT_M8VJEe-gzK1_i2VR3A" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXT_NMVJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXT_NcVJEe-gzK1_i2VR3A" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXT_NsVJEe-gzK1_i2VR3A" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXT_N8VJEe-gzK1_i2VR3A" name="SESS_NAME" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXT_OMVJEe-gzK1_i2VR3A" value="SESS_NAME"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXT_OcVJEe-gzK1_i2VR3A" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXT_OsVJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXT_O8VJEe-gzK1_i2VR3A" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXT_PMVJEe-gzK1_i2VR3A" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXT_PcVJEe-gzK1_i2VR3A" name="ACT_ID" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXT_PsVJEe-gzK1_i2VR3A" value="ACT_ID"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXT_P8VJEe-gzK1_i2VR3A" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXT_QMVJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXT_QcVJEe-gzK1_i2VR3A" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXT_QsVJEe-gzK1_i2VR3A" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXT_Q8VJEe-gzK1_i2VR3A" name="ACT_NAME" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXT_RMVJEe-gzK1_i2VR3A" value="ACT_NAME"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXT_RcVJEe-gzK1_i2VR3A" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXT_RsVJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXT_R8VJEe-gzK1_i2VR3A" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXT_SMVJEe-gzK1_i2VR3A" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXT_ScVJEe-gzK1_i2VR3A" name="ACT_ITER" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXT_SsVJEe-gzK1_i2VR3A" value="ACT_ITER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXT_S8VJEe-gzK1_i2VR3A" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_VXT_TMVJEe-gzK1_i2VR3A" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXT_TcVJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXT_TsVJEe-gzK1_i2VR3A" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXT_T8VJEe-gzK1_i2VR3A" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXT_UMVJEe-gzK1_i2VR3A" name="FILE_ID" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXT_UcVJEe-gzK1_i2VR3A" value="FILE_ID"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXT_UsVJEe-gzK1_i2VR3A" value="0"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_VXT_U8VJEe-gzK1_i2VR3A" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXT_VMVJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXT_VcVJEe-gzK1_i2VR3A" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXT_VsVJEe-gzK1_i2VR3A" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXT_V8VJEe-gzK1_i2VR3A" name="FILE_OPERATION" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXT_WMVJEe-gzK1_i2VR3A" value="FILE_OPERATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXT_WcVJEe-gzK1_i2VR3A" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXT_WsVJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXT_W8VJEe-gzK1_i2VR3A" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXT_XMVJEe-gzK1_i2VR3A" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXT_XcVJEe-gzK1_i2VR3A" name="FILE_NAME" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXT_XsVJEe-gzK1_i2VR3A" value="FILE_NAME"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXT_X8VJEe-gzK1_i2VR3A" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXT_YMVJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXT_YcVJEe-gzK1_i2VR3A" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXT_YsVJEe-gzK1_i2VR3A" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXT_Y8VJEe-gzK1_i2VR3A" name="FILE_DIR" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXT_ZMVJEe-gzK1_i2VR3A" value="FILE_DIR"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXT_ZcVJEe-gzK1_i2VR3A" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXT_ZsVJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXT_Z8VJEe-gzK1_i2VR3A" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXT_aMVJEe-gzK1_i2VR3A" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXT_acVJEe-gzK1_i2VR3A" name="FILE_FROM_DIR" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXT_asVJEe-gzK1_i2VR3A" value="FILE_FROM_DIR"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXT_a8VJEe-gzK1_i2VR3A" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXT_bMVJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXUmAMVJEe-gzK1_i2VR3A" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXUmAcVJEe-gzK1_i2VR3A" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXUmAsVJEe-gzK1_i2VR3A" name="FILE_FROM_FILE" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXUmA8VJEe-gzK1_i2VR3A" value="FILE_FROM_FILE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXUmBMVJEe-gzK1_i2VR3A" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXUmBcVJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXUmBsVJEe-gzK1_i2VR3A" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXUmB8VJEe-gzK1_i2VR3A" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXUmCMVJEe-gzK1_i2VR3A" name="FILE_TO_DIR" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXUmCcVJEe-gzK1_i2VR3A" value="FILE_TO_DIR"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXUmCsVJEe-gzK1_i2VR3A" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXUmC8VJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXUmDMVJEe-gzK1_i2VR3A" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXUmDcVJEe-gzK1_i2VR3A" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXUmDsVJEe-gzK1_i2VR3A" name="FILE_TO_FILE" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXUmD8VJEe-gzK1_i2VR3A" value="FILE_TO_FILE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXUmEMVJEe-gzK1_i2VR3A" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXUmEcVJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXUmEsVJEe-gzK1_i2VR3A" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXUmE8VJEe-gzK1_i2VR3A" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXUmFMVJEe-gzK1_i2VR3A" name="FILE_OPERATION_DATE" position="14">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXUmFcVJEe-gzK1_i2VR3A" value="FILE_OPERATION_DATE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXUmFsVJEe-gzK1_i2VR3A" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXUmF8VJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXUmGMVJEe-gzK1_i2VR3A" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXUmGcVJEe-gzK1_i2VR3A" value="25"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXUmGsVJEe-gzK1_i2VR3A" name="STATUS" position="15">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXUmG8VJEe-gzK1_i2VR3A" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXUmHMVJEe-gzK1_i2VR3A" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXUmHcVJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXUmHsVJEe-gzK1_i2VR3A" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXUmH8VJEe-gzK1_i2VR3A" value="35"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXUmIMVJEe-gzK1_i2VR3A" name="STATUS_COMMENT" position="16">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXUmIcVJEe-gzK1_i2VR3A" value="STATUS_COMMENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXUmIsVJEe-gzK1_i2VR3A" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXUmI8VJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXUmJMVJEe-gzK1_i2VR3A" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXUmJcVJEe-gzK1_i2VR3A" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXUmJsVJEe-gzK1_i2VR3A" name="STATUS_DATE" position="17">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXUmJ8VJEe-gzK1_i2VR3A" value="STATUS_DATE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXUmKMVJEe-gzK1_i2VR3A" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXUmKcVJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXUmKsVJEe-gzK1_i2VR3A" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXUmK8VJEe-gzK1_i2VR3A" value="25"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXUmLMVJEe-gzK1_i2VR3A" name="USER_COMMENT" position="18">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXUmLcVJEe-gzK1_i2VR3A" value="USER_COMMENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXUmLsVJEe-gzK1_i2VR3A" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXUmL8VJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXUmMMVJEe-gzK1_i2VR3A" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXUmMcVJEe-gzK1_i2VR3A" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXUmMsVJEe-gzK1_i2VR3A" name="USER_FLAG" position="19">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXUmM8VJEe-gzK1_i2VR3A" value="USER_FLAG"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXUmNMVJEe-gzK1_i2VR3A" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXUmNcVJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXUmNsVJEe-gzK1_i2VR3A" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXUmN8VJEe-gzK1_i2VR3A" value="35"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXUmOMVJEe-gzK1_i2VR3A" name="USER_DATE" position="20">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXUmOcVJEe-gzK1_i2VR3A" value="USER_DATE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXUmOsVJEe-gzK1_i2VR3A" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXUmO8VJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXUmPMVJEe-gzK1_i2VR3A" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXUmPcVJEe-gzK1_i2VR3A" value="25"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXUmPsVJEe-gzK1_i2VR3A" name="FILE_IS_HIDDEN" position="21">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXUmP8VJEe-gzK1_i2VR3A" value="FILE_IS_HIDDEN"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXUmQMVJEe-gzK1_i2VR3A" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_VXUmQcVJEe-gzK1_i2VR3A" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXUmQsVJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXUmQ8VJEe-gzK1_i2VR3A" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXUmRMVJEe-gzK1_i2VR3A" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXUmRcVJEe-gzK1_i2VR3A" name="FILE_LAST_MODIFIED" position="22">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXUmRsVJEe-gzK1_i2VR3A" value="FILE_LAST_MODIFIED"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXUmR8VJEe-gzK1_i2VR3A" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_VXUmSMVJEe-gzK1_i2VR3A" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXUmScVJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXUmSsVJEe-gzK1_i2VR3A" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXUmS8VJEe-gzK1_i2VR3A" value="20"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXUmTMVJEe-gzK1_i2VR3A" name="FILE_LAST_MODIFIED_DATE" position="23">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXUmTcVJEe-gzK1_i2VR3A" value="FILE_LAST_MODIFIED_DATE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXUmTsVJEe-gzK1_i2VR3A" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXUmT8VJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXUmUMVJEe-gzK1_i2VR3A" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXUmUcVJEe-gzK1_i2VR3A" value="25"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXUmUsVJEe-gzK1_i2VR3A" name="FILE_CAN_READ" position="24">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXUmU8VJEe-gzK1_i2VR3A" value="FILE_CAN_READ"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXUmVMVJEe-gzK1_i2VR3A" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_VXUmVcVJEe-gzK1_i2VR3A" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXUmVsVJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXUmV8VJEe-gzK1_i2VR3A" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXUmWMVJEe-gzK1_i2VR3A" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXUmWcVJEe-gzK1_i2VR3A" name="FILE_CAN_WRITE" position="25">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXUmWsVJEe-gzK1_i2VR3A" value="FILE_CAN_WRITE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXUmW8VJEe-gzK1_i2VR3A" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_VXUmXMVJEe-gzK1_i2VR3A" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXUmXcVJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXUmXsVJEe-gzK1_i2VR3A" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXUmX8VJEe-gzK1_i2VR3A" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXUmYMVJEe-gzK1_i2VR3A" name="FILE_CAN_EXECUTE" position="26">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXUmYcVJEe-gzK1_i2VR3A" value="FILE_CAN_EXECUTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXUmYsVJEe-gzK1_i2VR3A" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_VXUmY8VJEe-gzK1_i2VR3A" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXUmZMVJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXUmZcVJEe-gzK1_i2VR3A" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXUmZsVJEe-gzK1_i2VR3A" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXUmZ8VJEe-gzK1_i2VR3A" name="FILE_IS_DIRECTORY" position="27">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXUmaMVJEe-gzK1_i2VR3A" value="FILE_IS_DIRECTORY"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXUmacVJEe-gzK1_i2VR3A" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_VXUmasVJEe-gzK1_i2VR3A" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXUma8VJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXUmbMVJEe-gzK1_i2VR3A" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXUmbcVJEe-gzK1_i2VR3A" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_VXUmbsVJEe-gzK1_i2VR3A" name="FILE_LENGTH" position="28">
        <attribute defType="com.stambia.rdbms.column.name" id="_VXUmb8VJEe-gzK1_i2VR3A" value="FILE_LENGTH"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_VXUmcMVJEe-gzK1_i2VR3A" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_VXUmccVJEe-gzK1_i2VR3A" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_VXUmcsVJEe-gzK1_i2VR3A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_VXUmc8VJEe-gzK1_i2VR3A" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_VXUmdMVJEe-gzK1_i2VR3A" value="20"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_hyNHPNK-Ee-it8eojxI-6Q" name="ARCHIVE_SOURCE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_hyNHPdK-Ee-it8eojxI-6Q" value="ARCHIVE_SOURCE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_hyNHPtK-Ee-it8eojxI-6Q" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_hyNHP9K-Ee-it8eojxI-6Q" name="ID_SOURCE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_hyNHQNK-Ee-it8eojxI-6Q" value="ID_SOURCE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hyNHQdK-Ee-it8eojxI-6Q" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hyNHQtK-Ee-it8eojxI-6Q" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hyNHQ9K-Ee-it8eojxI-6Q" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hyNHRNK-Ee-it8eojxI-6Q" name="SOURCE" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_hyNHRdK-Ee-it8eojxI-6Q" value="SOURCE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hyNHRtK-Ee-it8eojxI-6Q" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hyNHR9K-Ee-it8eojxI-6Q" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hyNHSNK-Ee-it8eojxI-6Q" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hyNHSdK-Ee-it8eojxI-6Q" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hyNHStK-Ee-it8eojxI-6Q" name="DATE_INTEGRATION" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_hyNHS9K-Ee-it8eojxI-6Q" value="DATE_INTEGRATION"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hyNHTNK-Ee-it8eojxI-6Q" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_hyNHTdK-Ee-it8eojxI-6Q" value="6"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hyNHTtK-Ee-it8eojxI-6Q" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hyNHT9K-Ee-it8eojxI-6Q" value="TIMESTAMP(6)"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hyNHUNK-Ee-it8eojxI-6Q" value="11"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hyNHUdK-Ee-it8eojxI-6Q" name="STATUTS" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_hyNHUtK-Ee-it8eojxI-6Q" value="STATUTS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hyNHU9K-Ee-it8eojxI-6Q" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hyNHVNK-Ee-it8eojxI-6Q" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hyNHVdK-Ee-it8eojxI-6Q" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hyNHVtK-Ee-it8eojxI-6Q" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_hyNHV9K-Ee-it8eojxI-6Q" name="MOTIF" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_hyNHWNK-Ee-it8eojxI-6Q" value="MOTIF"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_hyNHWdK-Ee-it8eojxI-6Q" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_hyNHWtK-Ee-it8eojxI-6Q" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_hyNHW9K-Ee-it8eojxI-6Q" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_hyNHXNK-Ee-it8eojxI-6Q" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_hyNHXdK-Ee-it8eojxI-6Q" name="SYS_C0041107">
        <node defType="com.stambia.rdbms.colref" id="_hyNHXtK-Ee-it8eojxI-6Q" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_hyNHX9K-Ee-it8eojxI-6Q" ref="resource.md#_hyNHP9K-Ee-it8eojxI-6Q?fileId=_FZzs0LfJEe-iaoMtKSubDA$type=md$name=ID_SOURCE?"/>
        </node>
      </node>
    </node>
  </node>
</md:node>