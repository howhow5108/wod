# wod

匯入油猴可能亂碼, 請匯入後自行修改
75行
    const match = /^(?<rollType>.+)公式为：(?<rollCalculation>.+?)( \((?<modifier>[+\-]\d*%?)\))?$/g.exec( $( this ).text() );
98-102行
    replaced = replaced.replaceAll( '×', '*' );
    replaced = replaced.replaceAll( '÷', '/' );
    replaced = replaced.replaceAll( '２', '2' );
    replaced = replaced.replaceAll( '３', '3' );
    replaced = replaced.replaceAll( '＋', '+' );
